---
title: "Short-Term Electricity Demand Forecasting Using Low-Cost Signals and Gradient Boosting"
collection: publications
category: thesis
permalink: /en/publication/2026-08-01-prediccion-demanda-electrica
lang: en
translation_url: /publication/2026-08-01-prediccion-demanda-electrica
excerpt: 'Short-term time series forecasting (Short Term Load Forecasting) of electricity demand in the German market using low-cost signals (SMARD, Open-Meteo/ERA5) and a Gradient Boosting (Machine Learning) model with weekly retraining.'
date: 2026-08-01
venue: 'VIU (Valencia International University), Master''s Thesis'
paperurl: 'https://github.com/jmompou/simpleElectricityDemandForecaster/blob/main/Prediccio%CC%81n%20de%20demanda%20ele%CC%81ctrica%20bajo%20sen%CC%83ales%20de%20bajo%20coste%20y%20gradient%20boosting.pdf'
citation: 'Ibáñez Puertas, J. (2026). &quot;Short-Term Electricity Demand Forecasting Using Low-Cost Signals and Gradient Boosting.&quot; Master''s Thesis, Master''s in Artificial Intelligence, VIU.'
---

You can see the project running live, showing the forecasts, at [homerlinux.duckdns.org/smard](http://homerlinux.duckdns.org/smard).

**Abstract**

This master's thesis addresses a classic time series problem known as Short Term Load Forecasting. Specifically, it focuses on producing short-term forecasts of electricity demand in the German market, over horizons from hours to days. To meet this goal, an Open Source philosophy is applied, based on working with public, free and easily obtainable data. Electricity demand is obtained from a SMARD API, run by the federal agency Bundesnetzagentur. Weather data from the ten most populous German cities is also used, via the Open-Meteo/ERA5 API, along with data on German non-working days at the national level.

Using these signals, a one-step-ahead Gradient Boosting model is trained, able to chain its own hourly forecasts into a weekly forecast. Its main support is a Linux cron-type process that downloads data every hour into a local database and forces a weekly retraining.

The system's evaluation uses exclusively part of that log: 208 hourly observations between July 4 and July 12, 2026. Over the daily horizon the model achieves a mean error of 3.45%, while SMARD's official forecast reaches 4.03% over the 175 timestamps common to both. This should be read with caution, though: it is an apparent advantage, but obtained over a single summer week. At the one-hour horizon, the error drops to a MAPE of 1.50% and a MAE of about 717 MW; although it should be noted that here the model has an advantage, since it is a nowcasting case and is not comparable to the daily forecast.

There are indications that the model may outperform SMARD's official forecast over the daily horizon, but this conclusion should be taken with caution: it still needs to be formally verified with a Diebold-Mariano test and with more data, since the current result rests on a single evaluation week.

Everything observed in the project suggests that, indeed, easily obtainable signals can be used to achieve useful forecasts at the operational level.
