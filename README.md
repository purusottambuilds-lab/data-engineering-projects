
# Data Engineering Projects - purusottambuilds-lab

Data Engineering projects by **Purusottam Swain**

> Azure Data Engineering portfolio showcasing end-to-end pipeline development using Microsoft Azure services.

---

## Portfolio Projects

| # | Project | Tech Stack | Description | Status |
|---|---------|-------|-------------|--------|
| 001 | [azure-insurance-claims-pipeline](https://github.com/purusottambuilds-lab/001-azure-insurance-claims-pipeline) | ADF, Databricks, PySpark, Delta Lake, Azure SQL | PIngests raw insurance claims CSV, runs a data quality framework with scoring gate, applies multi-factor PySpark risk scoring, stores versioned Delta Lake output, loads to Azure SQL via JDBC with Gmail alerting | ✅ Complete |
| 002 | [azure-weather-lakehouse](https://github.com/purusottambuilds-lab/002-azure-weather-lakehouse) | ADF, Open-Meteo API, Databricks, PySpark, Delta Lake, Azure SQL | Ingests live hourly weather data for 4 Indian cities via REST API using ADF ForEach, implements Medallion Architecture (Bronze/Silver/Gold), detects anomalies, applies rolling window analytics and severity scoring | ✅ Complete |
| 003 | [stock-market-analytics-pipeline](https://github.com/purusottambuilds-lab/stock-market-analytics-pipeline) | ADF, Alpha Vantage API, Databricks, PySpark, Delta Lake, Azure SQL | Ingests daily stock price data via free API, implements SCD Type 2 history tracking using Delta MERGE, demonstrates Delta time travel, incremental loading pattern and broadcast variables | 🔄 In Progress |
| 004 | [retail-sales-data-warehouse](https://github.com/purusottambuilds-lab/retail-sales-data-warehouse) | ADF, REST Countries API, Kaggle Olist Dataset, Databricks, PySpark, Delta Lake, Azure SQL | Multi-source ingestion from CSV and REST API, builds star schema data warehouse with dim and fact tables, parameterized ADF pipelines, bucketing and partitioning strategies | ⏳ Planned |
| 005 | [github-activity-analytics](https://github.com/purusottambuilds-lab/github-activity-analytics) | ADF, GitHub API, Databricks, PySpark, Delta Lake | Ingests GitHub public events via REST API using ADF ForEach, processes developer activity metrics, builds productivity scoring with dynamic parameterized pipelines and Z-ordering | ⏳ Planned |

---


## 🛠️ Tech Stack

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

---

## Repository Structure

```
purusottambuilds-lab/
├── data-engineering-projects/     ← this repo (portfolio hub)
├── 001-azure-insurance-claims-pipeline/
├── 002-azure-weather-lakehouse/
└── 003-stock-market-pipeline/
```

---

## About

Built by **Purusottam Swain** - Azure Data Engineer
Specialising in cloud-native data pipelines on Microsoft Azure.

---

## 📬 Contact
- Email: purusottam.builds@gmail.com
- [Upwork](https://www.upwork.com/freelancers/~017164fcff771e794c?mp_source=share)
- [Fiverr](https://www.fiverr.com/purusottam_sn?public_mode=true)

---