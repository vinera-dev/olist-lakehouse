# olist-lakehouse

An analytics project on Databricks that turns a public Brazilian e-commerce dataset into a medallion lakehouse and an executive dashboard.

> **Status:** planned, not started. This README describes the intended scope.

## Purpose

Show data engineering and analytics work end to end: ingestion, layered transformations, data quality, business KPIs and data storytelling for decision makers.

## Data

The [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (CC BY-NC-SA 4.0). The raw files are not redistributed in this repository; download them from the original source.

## Planned scope

- Bronze, silver and gold layers on Databricks Free Edition (Delta tables)
- SQL and PySpark transformations
- Data quality checks (uniqueness, referential integrity, null and range rules)
- KPI marts: revenue, average order value, delivery performance, seller and category performance, customer retention
- Tableau Public dashboard with a clear narrative and executive summary
- Notes on using an AI assistant for exploratory analysis and how its results were verified

## Planned stack

Databricks, Delta Lake, SQL, PySpark, Tableau Public.

## Roadmap

- [ ] 1. Ingestion to the bronze layer
- [ ] 2. Silver layer: cleaning and modeling
- [ ] 3. Data quality checks
- [ ] 4. Gold layer: KPI marts
- [ ] 5. Dashboard and data storytelling
- [ ] 6. Documentation of methodology and findings

## License

Released under the [MIT License](LICENSE). The dataset keeps its own license.
