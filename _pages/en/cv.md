---
layout: archive
title: "CV"
permalink: /en/cv/
author_profile: true
lang: en
translation_url: /cv/
---

{% include base_path %}

Jorge Ibáñez Puertas — Data Scientist | Machine Learning | Python & SQL
Torrevieja, Spain (open to relocation, incl. Milan, and remote) • +34 722 720 048 • joorge.ibanez.puertas@gmail.com
linkedin.com/in/jorgeibanezpuertas • github.com/jmompou

<div class="cv-download-links">
  <a href="{{ base_path }}/files/CV_Jorge_Ibanez_Puertas_EN.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>

PROFILE
======
Mathematician (BSc) with an MSc in Artificial Intelligence and a year of professional experience building data models, SQL pipelines, and BI reporting used in production at client companies. I build things end to end, from raw data through modelling to a decision someone acts on. Academic distinction in pure mathematics, published applied optimisation research, and a first-principles approach to unfamiliar problems. Skilled in Python, SQL, TensorFlow, gradient boosting, and mathematical optimisation.

EDUCATION
======
* Master's in Artificial Intelligence — Valencia International University (VIU), Oct 2025 – Aug 2026
  * Focus: neural networks, computer vision, deep learning, machine learning, and data analysis. Grade: 7.75/10.
* BSc in Mathematics — UNED (National Distance Education University), Spain, 2018 – 2025
  * Completed alongside full-time work; exchange year at the Autonomous University of Madrid (UAM), 2022–23.
  * Highest honors (Matrícula de Honor) in Discrete Mathematics and Graph Theory.
* BSc (first year) in Aerospace Engineering — Delft University of Technology, NL, 2017 – 2018
  * Admitted on academic merit following the International Baccalaureate Diploma with Distinction (2017); transferred to Mathematics to follow my main interest.

PROJECTS
======
Code, write-ups, and the full publication list are on the [Portfolio](/portfolio/) and [Publications](/en/publications/) pages.

* Electricity Demand Forecasting from Low-Cost Signals — MSc Thesis, VIU, Feb 2026 – Aug 2026
  * Built an end-to-end Python forecasting pipeline predicting electricity demand from low-cost, open-source proxy signals rather than costly sensor data, training a LightGBM gradient boosting model on 88,111 hourly observations spanning 10 years.
  * Engineered 18 calendar, lag, and weather-proxy features; ran walk-forward validation across 7 forecast horizons (1–168 hours), cutting day-ahead mean absolute error to 1,733 MW from a 4,174 MW seasonal-naive baseline, and beating the grid operator's own official day-ahead forecast (1,733 MW vs. 1,893 MW).
* [Irrigation Coverage Optimisation](https://github.com/jmompou/pivotIrrigationSystem) — University of Murcia, with a working farm in Albacete, 2023 – present
  * Formulated and solved a mixed-integer nonlinear (MINLP) model in AMPL/Gurobi (145.9 ha parcel, 261 variables, 462 constraints) to find the cost-minimal number, placement, and size of center-pivot irrigation systems, from field data gathered on site with the farm owner (Explotación Agraria Puertas SL, Albacete).
  * Co-authored the resulting paper, published by the University of Murcia: Clemente Pérez, A., Ibáñez Puertas, J. & Colchero Truniger, N. (2023), *Ampliación del área de riego en una finca*.
  * Independently extended the project: reimplemented the model natively in Python (Pyomo, no AMPL dependency), added automatic farm-boundary extraction from satellite imagery, and am now reframing pivot placement as a reinforcement-learning problem (PyTorch PPO); released as open source on GitHub.
* [Inventory Models: Analysis and Applications](https://github.com/jmompou/inventoryModels) — BSc Thesis, UNED, 2025
  * Studied and mathematically modeled deterministic (EOQ and variants: lead times, quantity discounts, multi-item, storage constraints) and probabilistic inventory systems (continuous and periodic review, multi-period, safety stock), including perturbation methods for inspection errors and returns, plus a supporting literature review. Grade: 9.6/10.
* Almazen | Inventory Management Web App
  * Built a browser-based tool implementing 5 inventory policies (EOQ/Wilson, EOQ + safety stock, periodic review, single-period/newsvendor, min–max s-S) to generate reorder-point and order-quantity suggestions from real stock data, with movement tracking and SARIMA-style demand forecasting.
* An Unusual Path — Independent research paper, 2014
  * Wrote an independent mathematics research paper that won the VIII Prize for Secondary School Students awarded by the Department of Mathematics, Universidad Autónoma de Madrid.

EXPERIENCE
======
* Programmer & Data Analyst — Unidata, Murcia, Jun 2025 – Nov 2025
  * Designed data models and built SQL queries and stored procedures for ETL to the reporting layer behind real-time dashboards.
  * Developed automated BI dashboards and self-service reports; contributed to business applications used in production.
* Data Analyst Intern — NTT Data, Murcia, Jun 2022 – Sep 2022
  * Processed large datasets with Python and SQL; built Tableau dashboards for client reporting over a 3-month internship.
* Teaching & Research Assistant (internship) — University of Murcia, Faculty of Mathematics, Dec 2021 – Jun 2022
  * Supported teaching and research in Multivariable Calculus and Vector Analysis; prepared course materials.

SKILLS
======
* Programming: Python (Pandas, NumPy, TensorFlow, Keras), SQL, Git.
* Mathematical & optimisation software: R, MATLAB, AMPL, LaTeX.
* Statistics & modelling: statistical inference, time-series forecasting, gradient boosting, mathematical optimisation.
* Data & BI: data pipelines, data modelling & warehousing, Tableau, BI dashboarding.
* Recent coursework: Data Analysis and Visualisation: Practical Statistics with R and Artificial Intelligence (UNED, Sep 2025).
* Languages: Spanish (native); English C2, Cambridge Proficiency (CPE), 2026, Use of English 230/230.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
