---
title: "Predicción de demanda eléctrica a corto plazo mediante señales de bajo coste y Gradient Boosting"
collection: publications
category: thesis
permalink: /publication/2026-08-01-prediccion-demanda-electrica
excerpt: 'Predicción de series temporales a corto plazo (Short Term Load Forecasting) de la demanda eléctrica en el mercado alemán mediante señales de bajo coste (SMARD, Open-Meteo/ERA5) y un modelo Gradient Boosting con reentrenamiento semanal.'
date: 2026-08-01
venue: 'VIU (Universidad Internacional de Valencia), Trabajo de Fin de Máster'
citation: 'Ibáñez Puertas, J. (2026). &quot;Predicción de demanda eléctrica a corto plazo mediante señales de bajo coste y Gradient Boosting.&quot; Trabajo de Fin de Máster, Máster en Inteligencia Artificial, VIU.'
---

Puede ver el proyecto funcionando en vivo, mostrando las predicciones, en [homerlinux.duckdns.org/smard](http://homerlinux.duckdns.org/smard).

**Resumen**

Este trabajo de fin de máster aborda un problema clásico de series temporales conocido como Short Term Load Forecasting. En concreto, se centra en realizar predicciones a corto plazo de la demanda eléctrica en el mercado alemán, en horizontes de horas a días. Para cumplir este objetivo se aplica una filosofía Open Source, basada en tratar con datos públicos, gratuitos y de fácil obtención. La demanda eléctrica se obtiene a partir de una API de SMARD, de la agencia federal Bundesnetzagentur. Se usarán también los datos climáticos de las diez ciudades alemanas de mayor población mediante la API Open-Meteo/ERA5; y datos de días no laborables alemanes a nivel nacional.

Con dichas señales se lleva a cabo el entrenamiento de un modelo Gradient Boosting con predicción a un paso, capaz de encadenar sus propias previsiones horarias hasta una previsión semanal. Su apoyo principal es un proceso tipo cron en Linux, que descarga datos cada hora en una base de datos local y fuerza un reentrenamiento semanal.

La evaluación del sistema usa exclusivamente parte de ese registro: 208 observaciones horarias entre el 4 y el 12 de julio de 2026. En el horizonte diario el modelo comete un error medio del 3,45 %, mientras que la previsión oficial de SMARD alcanza un 4,03 % sobre las 175 marcas comunes a ambos. Ahora bien, esto se trata con cautela: es una ventaja aparente, pero se obtiene con una única semana de verano. A una hora, el error baja a un MAPE del 1,50 % y un MAE de unos 717 MW; aunque cabe decir que aquí el modelo juega con ventaja, es un caso de nowcasting y no es comparable con la previsión diaria.

Todo lo observado en el proyecto sugiere que, efectivamente, se pueden utilizar señales de fácil obtención para alcanzar predicciones útiles en el nivel operativo.
