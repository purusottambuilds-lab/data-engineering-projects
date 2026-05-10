into Azure SQL Database — scheduled weekly via ADF.

## Architecture
```
Raw CSV (Kaggle)
    |
    v
ADLS Gen2 [raw container]
    |
    v
Azure Data Factory Pipeline  <-- Weekly Trigger (Monday 8AM)
    |
    v
Azure Databricks + PySpark
  - Clean nulls, remove duplicates
  - Cast data types
  - Risk Score: HIGH / MEDIUM / LOW
    |
    v
Delta Lake [transformed container]  <-- Partitioned by risk_score
    |
    v
Azure SQL Database [dbo.insurance_claims_scored]
```

## Tech Stack
| Tool | Purpose |
|------|---------|
| Azure Data Factory V2 | Orchestration & weekly scheduling |
| Azure Data Lake Storage Gen2 | Raw & transformed storage |
| Azure Databricks (PySpark) | Transformation & risk scoring |
| Delta Lake | Partitioned versioned storage format |
| Azure SQL Database | Analytics-ready curated output |
