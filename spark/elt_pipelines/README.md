# ELT Data Pipelines using Databricks

PySpark scripts from **Section 39 – ELT Data Pipelines using Databricks** of the Udemy Data Engineering course.

## What is ELT?
**ELT (Extract, Load, Transform)** is the modern pipeline approach — raw data is loaded into a data lake first, then transformed in-place using Spark.

## Topics Covered (Section 39)
- Building end-to-end ELT pipelines on Databricks
- Reading raw data from cloud storage (GCS)
- Loading data into Delta Tables
- Transforming data using Spark SQL and PySpark
- Scheduling pipelines on Databricks

## Files in This Folder
| File | Description |
|------|-------------|
| `extract.py` | Reading raw files from GCS into Spark DataFrames |
| `load.py` | Writing DataFrames into Delta Tables |
| `transform.py` | Business transformations in Spark SQL |
| `pipeline.py` | End-to-end pipeline orchestration |

## Pipeline Flow
```
Raw Files (GCS) -> Extract -> Load (Delta raw) -> Transform -> Output (Delta cleansed)
```

## Progress
- [ ] Section 39 – ELT Data Pipelines using Databricks (0/13 lectures)
