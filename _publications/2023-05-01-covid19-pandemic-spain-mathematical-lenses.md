---
title: "The COVID19 pandemic in Spain through mathematical lenses"
collection: publications
category: projects
permalink: /publication/2023-05-01-covid19-pandemic-spain-mathematical-lenses
excerpt: 'Modelos compartimentales (SIR, SIRD, SEIQRD y modelos con vacunación) para estudiar la pandemia de COVID-19 en España, con ajuste numérico en Python.'
date: 2023-05-01
venue: 'Facultad de Matemáticas, Universidad de Murcia'
citation: 'Clemente Pérez, A., Ibáñez Puertas, J., &amp; Colchero Truniger, N. (2023). &quot;The COVID19 pandemic in Spain through mathematical lenses.&quot; Facultad de Matemáticas, Universidad de Murcia.'
---

Authors: Ana Clemente Pérez, Jorge Ibáñez Puertas, Nicolás Colchero Truniger.

**Abstract**

Este trabajo, realizado por estudiantes de la Facultad de Matemáticas de la Universidad de Murcia (mayo 2023), estudia la pandemia de COVID-19 en España mediante modelos compartimentales basados en sistemas de ecuaciones diferenciales ordinarias. Partiendo del modelo SIR clásico de Kermack y McKendrick (1927), se construyen cinco variantes de complejidad creciente: (1) un modelo SIRD que incorpora la población fallecida por la enfermedad y supone inmunidad permanente; (2) un modelo con pérdida gradual de inmunidad, que permite la reinfección e incluye nacimientos y muertes por causas ajenas al virus; (3) un modelo SEIQRD que añade los compartimentos de expuestos y de personas en cuarentena, junto con una tasa de detección; y (4) y (5) dos modelos de vacunación, uno en el que la vacuna confiere inmunidad total y otro en el que solo reduce las tasas de infección, mortalidad y exposición, duplicando la estructura del sistema para las poblaciones vacunada y no vacunada.

Para cada modelo se analiza la dinámica: puntos críticos, región invariante de soluciones factibles y, sobre todo, el número reproductivo básico R₀, cuyo valor determina si el sistema converge al equilibrio libre de enfermedad o si se produce un brote epidémico. Dado que los sistemas no admiten solución analítica, se resuelven numéricamente con scripts en Python (`scipy.integrate`, `lmfit`), que además ajustan los parámetros a datos reales semanales de casos y fallecidos por país y representan gráficamente la evolución de cada subpoblación.

La conclusión principal es que en todos los escenarios la epidemia se extingue si R₀ < 1, y que una cobertura vacunal suficiente permite reducir R₀ por debajo de ese umbral. No obstante, mientras virus y vacuna coexistan puede emerger una variante resistente, por lo que se recomienda vacunar con la mayor rapidez posible. Los autores señalan como limitaciones la escasez de datos (un punto por semana), la variabilidad temporal de la tasa de infección según las medidas aplicadas y el sobreajuste de parámetros cuando se seleccionan intervalos temporales cortos.
