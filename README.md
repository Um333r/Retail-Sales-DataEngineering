# Retail-Sales-DataEngineering
End-to-end Azure Databricks pipeline project using Unity Catalog, Delta Lake, and Power BI

# Retail Sales Data Engineering Project

This project demonstrates an end-to-end data pipeline using Azure + Databricks:
from ingesting raw sales data to producing business-ready dashboards.

## Tech Stack
- Azure Blob Storage
- Azure Databricks
- Unity Catalog
- Delta Lake
- Power BI

## Pipeline Overview

1. Bronze Layer - Raw data ingestion (CSV)
2. Silver Layer - Data cleansing and transformation
3. Gold Layer - Aggregations for dashboard/reporting

## Project Structure
retail-sales-data-pipeline/
│
├── data/ # Sample input datasets
├── notebooks/ # Databricks notebooks
├── docs/ # Architecture diagrams
├── dashboards/ # Power BI visualizations
└── README.md # Project overview.


## Key Learnings

- Implemented Lakehouse architecture using Delta Lake (Bronze-Silver-Gold)
- Managed data governance and security using Unity Catalog
- Automated ingestion and transformations using PySpark on Azure Databricks
- Built Power BI dashboards from Gold Layer tables

---

## Future Improvements

- Add CI/CD deployment for Databricks notebooks using GitHub Actions
- Integrate streaming data sources (Kafka or Event Hubs)
- Automate data quality checks and logging

---

## Author

**Mohammed Umar** 
Aspiring Data Engineer  
[LinkedIn](https://www.linkedin.com/in/mumarinsights/) | [GitHub](https://github.com/Um333r)
