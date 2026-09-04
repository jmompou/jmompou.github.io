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

Jorge Ibáñez Puertas — Científico de Datos | Machine Learning | Python y SQL
Torrevieja, España (abierto a reubicación, incl. Milán, y remoto) • +34 722 720 048 • joorge.ibanez.puertas@gmail.com
linkedin.com/in/jorgeibanezpuertas • github.com/jmompou

<div class="cv-download-links">
  <a href="{{ base_path }}/files/CV_Jorge_Ibanez_Puertas_EN.pdf" class="btn btn--primary">Descargar CV en PDF (inglés)</a>
</div>

PERFIL
======
Matemático (Grado) con un Máster en Inteligencia Artificial y un año de experiencia profesional construyendo modelos de datos, pipelines SQL e informes de BI usados en producción en empresas cliente. Trabajo de extremo a extremo, desde el dato en bruto hasta el modelado y la decisión que alguien toma a partir de él. Matrícula de Honor en matemática pura, investigación aplicada en optimización publicada, y un enfoque desde primeros principios ante problemas nuevos. Con experiencia en Python, SQL, TensorFlow, gradient boosting y optimización matemática.

FORMACIÓN
======
* Máster en Inteligencia Artificial — Universidad Internacional de Valencia (VIU), oct. 2025 – ago. 2026
  * Enfoque: redes neuronales, visión por computador, deep learning, machine learning y análisis de datos. Nota: 7,75/10.
* Grado en Matemáticas — UNED (Universidad Nacional de Educación a Distancia), España, 2018 – 2025
  * Cursado compatibilizándolo con trabajo a tiempo completo; año de intercambio en la Universidad Autónoma de Madrid (UAM), 2022–23.
  * Matrícula de Honor en Matemática Discreta y Teoría de Grafos.
* Primer curso del Grado en Ingeniería Aeroespacial — Delft University of Technology, Países Bajos, 2017 – 2018
  * Admitido por mérito académico tras obtener el Diploma de Bachillerato Internacional con Distinción (2017); se trasladó a Matemáticas para seguir su principal interés.

PROYECTOS
======
El código, los artículos y el listado completo de publicaciones están en las páginas de [Portafolio](/portfolio/) y [Publicaciones](/publications/).

* Predicción de la demanda eléctrica mediante señales de bajo coste — Trabajo de Fin de Máster, VIU, feb. 2026 – ago. 2026
  * Desarrollo de un pipeline de predicción de extremo a extremo en Python que estima la demanda eléctrica a partir de señales proxy de bajo coste y open-source, en lugar de datos de sensores costosos, entrenando un modelo de gradient boosting (LightGBM) sobre 88.111 observaciones horarias a lo largo de 10 años.
  * Diseño de 18 variables de calendario, retardos y proxies meteorológicos; validación walk-forward en 7 horizontes de predicción (de 1 a 168 horas), reduciendo el error absoluto medio a 24 horas vista a 1.733 MW frente a los 4.174 MW de la referencia estacional ingenua, y superando la propia previsión oficial del operador del sistema eléctrico (1.733 MW frente a 1.893 MW).
* [Optimización de la cobertura de riego](https://github.com/jmompou/pivotIrrigationSystem) — Universidad de Murcia, con una finca en explotación en Albacete, 2023 – actualidad
  * Formulación y resolución de un modelo mixto entero no lineal (MINLP) en AMPL/Gurobi (parcela de 145,9 ha, 261 variables, 462 restricciones) para determinar el número, la ubicación y el tamaño óptimos, al menor coste, de sistemas de riego por pivote central, a partir de datos de campo recogidos junto al propietario de la finca (Explotación Agraria Puertas SL, Albacete).
  * Coautoría del artículo resultante, publicado por la Universidad de Murcia: Clemente Pérez, A., Ibáñez Puertas, J. & Colchero Truniger, N. (2023), *Ampliación del área de riego en una finca*.
  * Ampliación independiente del proyecto: reimplementación nativa del modelo en Python (Pyomo, sin dependencia de AMPL), extracción automática del contorno de la finca a partir de imágenes satelitales, y reformulación en curso de la colocación de pivotes como un problema de aprendizaje por refuerzo (PyTorch PPO); publicado como código abierto en GitHub.
* [Modelos de Inventario: Análisis y algunas aplicaciones](https://github.com/jmompou/inventoryModels) — Trabajo de Fin de Grado, UNED, 2025
  * Estudio y modelización matemática de sistemas de inventario deterministas (EOQ y variantes: plazos de entrega, descuentos por cantidad, multi-artículo, restricciones de almacenamiento) y probabilistas (revisión continua y periódica, multi-periodo, stock de seguridad), incluyendo métodos de perturbación para errores de inspección y devoluciones, junto con una revisión de la literatura. Nota: 9,6/10.
* Almazen | Aplicación web de gestión de inventario
  * Herramienta web que implementa 5 políticas de inventario (EOQ/Wilson, EOQ + stock de seguridad, revisión periódica, periodo único/newsvendor, min–max s-S) para generar sugerencias de punto de pedido y cantidad a pedir a partir de datos reales de stock, con seguimiento de movimientos y previsión de demanda estilo SARIMA.
* Un camino inusual — Trabajo de investigación independiente, 2014
  * Trabajo de investigación matemática independiente, ganador del VIII Premio para Estudiantes de Secundaria del Departamento de Matemáticas de la Universidad Autónoma de Madrid.

EXPERIENCIA
======
* Programador y Analista de Datos — Unidata, Murcia, jun. 2025 – nov. 2025
  * Diseño de modelos de datos y desarrollo de consultas SQL y procedimientos almacenados para ETL hacia la capa de reporting de dashboards en tiempo real.
  * Desarrollo de dashboards de BI automatizados e informes de autoservicio; contribución a aplicaciones de negocio en producción.
* Analista de Datos en prácticas — NTT Data, Murcia, jun. 2022 – sep. 2022
  * Procesamiento de grandes volúmenes de datos con Python y SQL; desarrollo de dashboards en Tableau para reporting a cliente durante una beca de 3 meses.
* Ayudante de docencia e investigación (prácticas) — Universidad de Murcia, Facultad de Matemáticas, dic. 2021 – jun. 2022
  * Apoyo a la docencia e investigación en Cálculo Multivariable y Análisis Vectorial; preparación de material docente.

APTITUDES
======
* Programación: Python (Pandas, NumPy, TensorFlow, Keras), SQL, Git.
* Software matemático y de optimización: R, MATLAB, AMPL, LaTeX.
* Estadística y modelización: inferencia estadística, series temporales, gradient boosting, optimización matemática.
* Datos y BI: pipelines de datos, modelización y almacenamiento de datos, Tableau, dashboarding de BI.
* Formación reciente: Análisis y Visualización de Datos: Estadística Práctica con R e Inteligencia Artificial (UNED, sep. 2025).
* Idiomas: español (nativo); inglés C2: Cambridge Proficiency (CPE), 2026, Use of English 230/230.

Publicaciones
======
  <ul>{% for post in site.publications reversed %}
    {% if post.lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
