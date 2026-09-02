---
title: "Ampliación del área de riego en una finca"
collection: publications
category: projects
permalink: /publication/2023-08-01-increasing-irrigation-area-farm
author: "Jorge Ibáñez Puertas (ES)"
lang: es
translation_url: /en/publication/2023-08-01-increasing-irrigation-area-farm
excerpt: 'Optimización mixta entera no lineal (AMPL + Gurobi) para rediseñar la disposición de pivotes de riego de una finca de 145,88 ha en La Grajuela (Albacete).'
date: 2023-08-01
venue: 'Universidad de Murcia (tutores: José Fernández, Manuel Pulido)'
citation: 'Clemente Pérez, A., Ibáñez Puertas, J., &amp; Colchero Truniger, N. (2023). &quot;Ampliación del área de riego en una finca.&quot; Universidad de Murcia.'
---

Tutores: José Fernández, Manuel Pulido

Autores: Ana Clemente Pérez, Jorge Ibáñez Puertas, Nicolás Colchero Truniger

**Resumen**

Este trabajo aborda el problema de rediseñar la disposición de riego de una finca de 145,88 ha en La Grajuela (Albacete), explotada por Explotación Agraria Puertas SL, cuya maquinaria de pivotes centrales se instaló hace cuatro décadas. El objetivo es determinar el número, la ubicación y el tamaño de los pivotes centrales que minimizan el coste total de riego de la parcela, cubriendo con riego por aspersión el área que quede fuera del alcance de los pivotes.

La parcela, de forma irregular, se aproxima como una unión de polígonos convexos. Las coordenadas de sus vértices se obtuvieron a partir de imágenes aéreas mediante un script en Python y después se reescalaron para que las distancias entre puntos consecutivos coincidan con las medidas reales tomadas del SIGPAC. Los precios por tramo se estimaron mediante un razonamiento de tipo regresión sobre seis instalaciones de pivotes conocidas en la zona.

El modelo resultante, de optimización mixta entera no lineal, implementado en AMPL y resuelto con Gurobi, sitúa el centro de cada pivote dentro de la parcela, obliga a que la distancia de cada centro a todos los segmentos del contorno supere el radio del pivote, y evita que los pivotes se solapen entre sí. La longitud de cada pivote se construye a partir de tramos de 37–54 m, con como máximo dos longitudes de tramo distintas y un radio máximo de 800 m.

La solución óptima instala tres pivotes de radios 270, 312 y 364 m, una disposición casi idéntica a la existente, lo que indica que la configuración actual ya está cerca del óptimo.
