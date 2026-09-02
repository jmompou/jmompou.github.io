---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
author: "Jorge Ibáñez Puertas (ES)"
lang: es
translation_url: /en/cv/
redirect_from:
  - /resume
---

{% include base_path %}

Jorge Ibáñez Puertas — Torrevieja, España (abierto a reubicación / remoto) • joorge.ibanez.puertas@gmail.com
linkedin.com/in/jorgeibanezpuertas • github.com/jmompou

PERFIL
======
Matemático (Grado, UNED) con un Máster en Inteligencia Artificial (VIU) y formación avanzada en econometría e inferencia causal (regresión, series temporales, diseño experimental), con experiencia práctica en Python, SQL y BI. Inglés fluido (C2, Cambridge CPE).

FORMACIÓN
======
* Máster en Inteligencia Artificial — Universidad Internacional de Valencia (VIU), oct. 2025 – ago. 2026
  * Enfoque: redes neuronales, visión por computador, deep learning (Python, TensorFlow/Keras).
  * Trabajo de Fin de Máster: «Predicción de demanda eléctrica mediante señales de bajo coste y Gradient Boosting».
* Grado en Matemáticas — UNED (Universidad Nacional de Educación a Distancia), España, 2018 – 2025
  * Año de intercambio en la Universidad Autónoma de Madrid (UAM), 2022–23.
  * Trabajo de Fin de Grado: «Modelos de Inventario: Análisis y algunas aplicaciones».
  * Matrícula de Honor en Matemática Discreta y Teoría de Grafos.
* Primer curso del Grado en Ingeniería Aeroespacial — Delft University of Technology, Países Bajos, 2017 – 2018

EXPERIENCIA
======
* Programador y Analista de Datos — Unidata, Murcia, jun. 2025 – nov. 2025
  * Diseño de modelos de datos y desarrollo de consultas SQL y procedimientos almacenados para ETL hacia la capa de reporting de dashboards en tiempo real.
  * Desarrollo de dashboards de BI automatizados e informes de autoservicio; contribución a aplicaciones de negocio en producción.
* Investigación Operativa — Explotación Agraria Puertas, Albacete, ago. 2023 – feb. 2024
  * Desarrollo de software de optimización de cobertura de riego en AMPL; mejora de la eficiencia en el uso del agua (código en GitHub).
  * Configuración de bases de datos y métricas de rendimiento para apoyar la toma de decisiones.
* Analista de Datos en prácticas — NTT Data, Murcia, jun. 2022 – sep. 2022
  * Procesamiento de grandes volúmenes de datos con Python y SQL; desarrollo de dashboards en Tableau para reporting a cliente.
* Ayudante de docencia e investigación (prácticas) — Universidad de Murcia, dic. 2021 – jun. 2022
  * Apoyo a la docencia e investigación en Cálculo Multivariable y Análisis Vectorial; preparación de material docente.

APTITUDES
======
* Programación: Python (Pandas, NumPy, TensorFlow, Keras), SQL, Java.
* Software matemático: R, MATLAB, Mathematica, AMPL, LaTeX.
* Estadística y econometría: diseño experimental, análisis de regresión, series temporales, inferencia causal, optimización.
* Datos y BI: Tableau, dashboarding de BI, almacenamiento de datos en SQL.
* Idiomas: español (nativo); inglés C2: Cambridge Proficiency (CPE), 2026.

PREMIOS
======
* Diploma de Bachillerato Internacional con Distinción, 2017.
* Ganador del VIII Premio para Estudiantes de Secundaria, Departamento de Matemáticas, Universidad Autónoma de Madrid (UAM), 2014, por el trabajo de investigación «Un camino inusual».

Publicaciones
======
  <ul>{% for post in site.publications reversed %}
    {% if post.lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
