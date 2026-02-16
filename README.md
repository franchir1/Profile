
# Riccardo Franchi

Junior Data Analyst with an engineering background, focused on **analytically correct data modeling and KPI definition**.

I started working on data analysis and data modeling in **October 2025**.  
My work is built as a structured learning and portfolio path based on **end-to-end analytical projects** developed on real-world datasets.

The focus across projects is on:
- data quality validation
- dimensional modeling
- explicit control of data granularity
- KPI design aligned with the analytical grain
- reproducibility and documentation clarity

---

## Core Skills

- **SQL (PostgreSQL)**  
  Analytical queries, JOINs, CTEs, aggregations, window functions, time-based analysis, KPI-oriented views

- **Data Modeling**  
  Star schema design, explicit fact table grain definition, dimension normalization, surrogate keys, bridge-table handling where required

- **BI & Analytics**  
  KPI definition, normalized metrics, comparative and diagnostic analysis, semantic consistency checks

- **Power BI**  
  Semantic modeling, DAX measures, KPI-driven dashboards, model validation and filter-context control

- **Excel / Power Query**  
  ETL, Power Pivot, pivot tables, analytical formulas

- **Documentation & Versioning**  
  Markdown documentation, GitHub-based analytical portfolios, layered project structure (STAGING → ANALYSIS → MART)

---

## Featured Projects

### NYC Restaurant Inspections — SQL Analytics  
🔗 https://github.com/franchir1/nyc_restaurant_inspections_sql

End-to-end analytical project based on NYC Department of Health and Mental Hygiene (DOHMH) restaurant inspection data.

The dataset presents structural challenges: no stable inspection identifier and multiple violation rows per inspection. The project was redesigned to enforce **inspection-level analytical grain** and prevent metric distortion.

**Key improvements**
- Reconstructed inspection-level fact logic with explicit grain declaration  
- Controlled handling of one-to-many violation relationships  
- Separation of STAGING (raw standardization), ANALYSIS (structural modeling), and MART (KPI-ready views)  
- Explicit deduplication and consistency validation checks  
- Revalidated KPIs to eliminate score inflation caused by violation-level duplication  

**Analytical outputs**
- Temporal trend analysis of inspection scores  
- Borough-level and cuisine-level comparisons  
- KPI views with validated denominators  
- Documented modeling assumptions and structural trade-offs  

---

### Olist E-commerce — Power BI Dashboard  
🔗 https://github.com/franchir1/olist_ecommerce_powerbi

Business-oriented analytical dashboard built on the **Olist Brazilian E-commerce public dataset** (100k orders, 2016–2018), integrating orders, payments, customers, products, sellers, reviews, and geolocation.

The project was restructured to strengthen semantic consistency and metric normalization across multiple transactional tables.

**Key improvements**
- Refined Power Query STAGING layer with explicit column typing and controlled transformations  
- Clear fact table grain definition at order level  
- Structural control over payment and order-item multiplicity  
- Alignment between data model relationships and KPI intent  
- Reduced ambiguity in filter propagation  

**DAX and modeling focus**
- Revenue normalized at correct transactional grain  
- Average Order Value aligned with order-level denominator  
- Delivery performance metrics based on validated date logic  
- Payment-type breakdown without double counting  
- Separation between analytical model and presentation layer  

**Dashboard scope**
- Sales and revenue trends  
- Geographic and customer performance  
- Product category contribution  
- Operational delivery indicators  

---

### US Flights — Flight Delay Analysis (SQL)  
🔗 https://github.com/franchir1/us_flights_analysis_sql

Analytical project based on US DOT On-Time Performance flight data.

The project enforces a **one-row-per-operated-flight grain**, with explicit semantic exclusions and KPI normalization rules.

**Key improvements**
- Refined fact table with composite natural key and surrogate support  
- Explicit exclusion logic for cancelled and diverted flights  
- Consistent delay definitions across metrics  
- MART layer redesigned for BI consumption  
- Structural separation between raw ingestion and analytical model  

**KPI outputs**
- Delay frequency by carrier and airport  
- Average arrival delay with validated denominator  
- Comparative carrier performance  
- Time-based delay patterns  

---

## Analytical Principles

Across projects, I consistently apply:

- Non-aggregating ETL and early data quality validation  
- Explicit fact table grain definition before analysis  
- KPI normalization using appropriate denominators  
- Verification of analytical assumptions before comparison  
- Clear separation between signal and noise in metrics  
- Separation between raw data, analytical model, and consumption layer  

---

## Background

- **MSc in Materials Engineering and Nanotechnology**  
  Politecnico di Torino  

- Professional experience in:
  - Field Service Engineering  
  - Sales Engineering  

with direct exposure to operational data, KPIs, and reporting in industrial contexts.

---

## Contacts

- Email: riccardo.franchi@outlook.com  
- LinkedIn: https://www.linkedin.com/in/riccardo-franchi-b8413a235  
- GitHub: https://github.com/franchir1
