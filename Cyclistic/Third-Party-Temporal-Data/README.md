# Third-Party-Temporal-Data
**Supporting SQL — Cyclistic Bike-Share Marketing Analysis**

---

## Overview

This folder contains the supporting SQL queries developed to enrich the Cyclistic bike-share dataset with third party temporal data. The introduction of holidays and weather patterns as contextual variables surfaced geospatial and behavioral questions that the core R analysis alone could not resolve — and laid the groundwork for Phase 2 of the Cyclistic project.

---

## Contents

### Cyclistic
Core SQL queries supporting the main Cyclistic analysis — ride length, ride counts, member vs. casual comparisons, mode analysis, origin/destination patterns, and seasonal and quarterly breakdowns.

### Holidays
SQL queries analyzing the relationship between ridership behavior and holiday patterns — including peak ridership on holidays, rider behavior breakdowns by holiday type, and the impact of holidays on overall ridership.

### Weather
SQL queries examining the impact of weather conditions on ridership — including temperature effects, precipitation impact, humidity, and wind — across both member and casual rider segments.

---

## Purpose

These queries were developed as part of the Cyclistic Phase 1 methodology to contextualize rider behavior beyond the raw trip data. The patterns surfaced here — particularly the intersection of temporal, weather, and geographic variables — are what Phase 2 is designed to answer visually through a ClickHouse pipeline powering a Tableau animated geospatial visualization.

---

*Part of the [Cyclistic Bike-Share Marketing Analysis](https://github.com/CosbyCD/Data-Analytics-Portfolio/tree/main/Cyclistic)*
