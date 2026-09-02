---
title: "Increasing the irrigation area on a farm"
collection: publications
category: projects
permalink: /en/publication/2023-08-01-increasing-irrigation-area-farm
lang: en
translation_url: /publication/2023-08-01-increasing-irrigation-area-farm
excerpt: 'Mixed-integer non-linear optimization (AMPL + Gurobi) to redesign the center-pivot irrigation layout of a 145.88 ha farm in La Grajuela (Albacete).'
date: 2023-08-01
venue: 'Universidad de Murcia (advisors: José Fernández, Manuel Pulido)'
citation: 'Clemente Pérez, A., Ibáñez Puertas, J., &amp; Colchero Truniger, N. (2023). &quot;Increasing the irrigation area on a farm.&quot; Universidad de Murcia.'
---

Advisor: José Fernández, Manuel Pulido

Authors: Ana Clemente Pérez, Jorge Ibáñez Puertas, Nicolás Colchero Truniger

**Abstract**

This work addresses the problem of redesigning the irrigation layout of a 145.88 ha farm in La Grajuela (Albacete), operated by Explotación Agraria Puertas SL, whose center pivot machinery was installed four decades ago. The goal is to determine the number, location and size of the center pivots that minimize the total cost of irrigating the parcel, with the area left uncovered by pivots irrigated by sprinkler coverage.

The irregular parcel is approximated as a union of convex polygons. Its corner coordinates were obtained from aerial imagery through a Python script and then rescaled so that the distances between consecutive points match the real measurements taken from SIGPAC. Section prices were estimated by regression-like reasoning on six known pivot installations in the area.

The resulting mixed-integer non-linear model, implemented in AMPL and solved with Gurobi, locates each pivot center inside the parcel, forces the point-to-segment distance from the center to every boundary edge to exceed the pivot radius, and prevents pivots from overlapping. Pivot length is built from spans of 37–54 m, with at most two different span lengths and a maximum radius of 800 m.

The optimal solution installs three pivots of radii 270, 312 and 364 m, an arrangement almost identical to the existing one, indicating that the current layout is already close to optimal.
