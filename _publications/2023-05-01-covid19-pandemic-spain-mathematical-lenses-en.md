---
title: "The COVID19 pandemic in Spain through mathematical lenses"
collection: publications
category: projects
permalink: /en/publication/2023-05-01-covid19-pandemic-spain-mathematical-lenses
lang: en
translation_url: /publication/2023-05-01-covid19-pandemic-spain-mathematical-lenses
excerpt: 'Compartmental models (SIR, SIRD, SEIQRD and vaccination models) to study the COVID-19 pandemic in Spain, with numerical fitting in Python.'
date: 2023-05-01
venue: 'Facultad de Matemáticas, Universidad de Murcia'
citation: 'Clemente Pérez, A., Ibáñez Puertas, J., &amp; Colchero Truniger, N. (2023). &quot;The COVID19 pandemic in Spain through mathematical lenses.&quot; Facultad de Matemáticas, Universidad de Murcia.'
---

Authors: Ana Clemente Pérez, Jorge Ibáñez Puertas, Nicolás Colchero Truniger.

**Abstract**

This work, carried out by students of the Faculty of Mathematics at the Universidad de Murcia (May 2023), studies the COVID-19 pandemic in Spain using compartmental models based on systems of ordinary differential equations. Starting from the classic SIR model by Kermack and McKendrick (1927), five variants of increasing complexity are built: (1) a SIRD model that incorporates the population that died from the disease and assumes permanent immunity; (2) a model with gradual loss of immunity, which allows reinfection and includes births and deaths from causes unrelated to the virus; (3) a SEIQRD model that adds the exposed and quarantined compartments, together with a detection rate; and (4) and (5) two vaccination models, one in which the vaccine confers full immunity and another in which it only reduces infection, mortality and exposure rates, duplicating the system's structure for the vaccinated and unvaccinated populations.

For each model the dynamics are analyzed: critical points, the invariant region of feasible solutions and, above all, the basic reproduction number R₀, whose value determines whether the system converges to the disease-free equilibrium or an epidemic outbreak occurs. Since the systems do not admit an analytical solution, they are solved numerically with Python scripts (`scipy.integrate`, `lmfit`), which also fit the parameters to real weekly data on cases and deaths per country and graphically represent the evolution of each subpopulation.

The main conclusion is that in every scenario the epidemic dies out if R₀ < 1, and that sufficient vaccination coverage makes it possible to bring R₀ below that threshold. However, as long as the virus and the vaccine coexist, a resistant variant may emerge, which is why it is recommended to vaccinate as quickly as possible. The authors note as limitations the scarcity of data (one point per week), the temporal variability of the infection rate depending on the measures applied, and parameter overfitting when short time intervals are selected.
