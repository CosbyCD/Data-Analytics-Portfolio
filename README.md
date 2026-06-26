# Data Analytics Portfolio
Cherrie Cosby [linkedin.com/in/cherriecosby](https://linkedin.com/in/cherriecosby) | [cherriecosby@gmail.com](mailto:cherriecosby@gmail.com)

A portfolio of completed and in-progress data analysis projects spanning SQL, R, Python, Excel, and Tableau — each built from raw data through cleaning, modeling, analysis, and published deliverable. Projects reflect real analytical questions, documented methodology, and results that hold up under scrutiny.

---

## Projects

### Cyclistic Bike-Share Marketing Analysis
Tools: PostgreSQL · R · VBA · Excel · SQL · ClickHouse · Tableau | Status: Phase 1 complete — Phase 2 published

**Published:**
- [Cyclistic Bike Share Phase 2 — Tableau Public](https://public.tableau.com/app/profile/cdcosby/viz/CyclisticBikeShareAnalysisRidershipPatternsConversionInsights/CyclisticBikeSharePhase2Analysis)
- [Analysis Report — Phase 1 (RPubs)](https://rpubs.com)
- [Methodology & Code — Phase 1 (RPubs)](https://rpubs.com)

**Phase 1 — Complete:** End-to-end ETL pipeline built from scratch — raw CSV data preprocessed through VBA, loaded into a custom-built PostgreSQL data warehouse, analyzed and visualized in R, and published as a full report with documented methodology. Production-grade SQL including window functions, CTEs, time-series analysis, and pivot operations. The introduction of third party temporal data — holidays and weather patterns — to contextualize rider behavior surfaced geospatial questions that R alone could not resolve. Those questions may hold answers with greater impact on the analytical question than Phase 1 was able to offer.

**Phase 2 — Published:** Built a ClickHouse Cloud pipeline ingesting 5.6M+ rows of Divvy ride data enriched with Visual Crossing weather data (27 fields), Chicago-specific holiday data (55 records), and lunar phase data — connected to Tableau Desktop via MySQL interface. The enrichment surfaced findings nobody in the dataset had identified: Independence Day ranks 12th in total ridership volume but 1st in casual conversion rate at 60.75%. Two separate weather and transit emergencies revealed Cyclistic bikes functioning as emergency mobility infrastructure. A B2G city partnership opportunity was identified from flooding and transit failure data. Five dashboards and a 10-point storyboard narrative published to Tableau Public.

Analytical question: How do annual members and casual riders use Cyclistic bikes differently, and what does that mean for a conversion-focused marketing strategy?

---

### Lariat Car Rental — Revenue Analysis & Strategic Scenarios
Tools: Microsoft Excel (Advanced) — Pivot Tables · Slicers · Charts · Dimensional Modeling · SUM · AVERAGE | Status: Complete

**Published:** [Excel Workbook](https://github.com/CosbyCD/Data-Analytics-Portfolio/tree/main/Lariat)

Built dimensionally across multiple sheets — source data, analysis layers, and scenario models each occupying their own structured space with formula transparency preserved throughout. Pivot tables and slicers drive the performance analysis; charts translate the numbers into visual story. Three strategic scenarios developed for 2019 revenue improvement — inventory growth (+$65,734), location performance reallocation, and inventory reinvestment (+$96,445) — each with full supporting calculations. The same dimensional thinking applied here is what I brought to every analytical role before it had a name.

Analytical question: Which strategic levers — inventory, location, or reinvestment — offer the strongest path to revenue growth, and by how much?

---

### COVID-19 Containment Measures — Global vs. U.S. Analysis
Tools: Python · Kaggle Datasets · Tableau (in development) | Status: Phase 1 complete — Phase 2 in development

Comparative time-series analysis of COVID-19 confirmed infection data examining whether global containment measures were more effective than those implemented in the United States.

Datasets:
- Global COVID-19 confirmed time series — 1/22/2020 to 12/30/2020 (271 rows × 348 columns)
- U.S. COVID-19 confirmed time series — 1/22/2020 to 12/07/2020 (3,340 rows × 332 columns)

Methods: Dataset exploration, merge, clean, and model; datetime, integer, and float data types; trend identification and wave pattern visualization; statistical testing to validate findings. Analysis focused on percent of total infection rates, Global vs. U.S.

**Phase 2 — In Development:** Building a ClickHouse pipeline to support a Tableau animated geospatial visualization — mapping infection wave patterns across countries over time with full temporal animation.

Hypothesis: Global containment measures would show a statistically meaningful correlation with lower infection rates compared to U.S. measures over the same period.

---

### Gridlots Superstore — Retail Sales Analysis
Tools: Tableau | Status: Complete

**Published:** [Tableau Dashboard](https://public.tableau.com)

Multi-dashboard Tableau story analyzing two years of retail sales data across regions, departments, cities, and store footprint — including year-over-year breakdowns, quarterly trends, bottom-performer identification, percentage-of-total analysis, sales-per-SQFT comparisons, and forward projections.

Analytical question: Where are the performance gaps, and what does the data say about where to focus next?

---

## Technical Stack

| Category | Tools |
|---|---|
| Databases & Query | SQL · PostgreSQL · ClickHouse · Microsoft Access |
| Programming | R · Python · VBA |
| Visualization | Tableau · R (ggplot2) · Excel Charts |
| ETL & Data Prep | Custom PostgreSQL pipeline · VBA preprocessing · Python (pandas) · ClickHouse |
| Productivity | Advanced Excel · RPubs |

---

*See [Current Projects](https://github.com/CosbyCD/Current-Projects) for what's actively in progress.*
