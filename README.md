# Data Engineering Practice

Practice code from the Udemy course **Data Engineering for Beginners: Learn SQL, Python & Spark** by ITVersity.

> Course: https://www.udemy.com/course/data-engineering-essentials-sql-python-and-spark/

---

## Repository Structure

```
data-engineering-practice/
├── sql/                          # SQL queries and exercises (PostgreSQL)
│   ├── basic_queries/            # SELECT, WHERE, JOINs, GROUP BY, ORDER BY
│   ├── aggregations_ranking/     # Window functions, cumulative aggregations
│   ├── troubleshooting/          # SQL debugging and error handling
│   ├── performance_tuning/       # Query optimisation, indexes, execution plans
│   └── exercises/                # Practice exercises and solutions
├── python/                       # Python scripts for data engineering
│   ├── basics/                   # Python fundamentals
│   ├── collections/              # Lists, dicts, sets, tuples
│   ├── pandas/                   # DataFrame operations, filtering, joins
│   ├── troubleshooting/          # Debugging and error handling
│   └── performance_tuning/       # Optimising Python pipelines
├── spark/                        # Apache Spark (PySpark) code
│   ├── spark_sql/                # Spark SQL queries and Delta Tables
│   ├── pyspark_df_apis/          # PySpark DataFrame API scripts
│   ├── elt_pipelines/            # ELT pipelines using Databricks
│   ├── performance_tuning/       # Catalyst Optimizer, partitioning, file formats
│   └── hadoop_spark_cluster/     # Hadoop HDFS, Hive, Dataproc applications
├── projects/                     # End-to-end data engineering projects
│   ├── file_format_converter/    # Project 1: Convert CSV/JSON/Parquet formats
│   └── db_loader/                # Project 2: Load files into a Postgres database
└── notes/                        # Personal notes and summaries per section
```

---

## Technologies Covered

| Technology | Purpose |
|-----------|---------|
| **PostgreSQL** | Relational database for SQL practice |
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **Apache Spark / PySpark** | Big data distributed processing |
| **Databricks (GCP)** | Managed Spark environment |
| **Google Cloud Platform** | Cloud infrastructure |
| **Hadoop / HDFS / Hive** | Big data ecosystem |

---

## Course Progress

### Module 1 — SQL (Sections 1–10)
- [x] Section 1 – Introduction to Data Engineering
- [x] Section 2 – Getting Started with SQL
- [x] Section 3 – Setup Tools
- [x] Section 4 – Setup Application Tables and Data in Postgres
- [x] Section 5 – Writing Basic SQL Queries
- [ ] Section 6 – Cumulative Aggregations and Ranking
- [ ] Section 7 – SQL Troubleshooting and Debugging
- [ ] Section 8 – Performance Tuning of SQL Queries
- [ ] Sections 9 & 10 – Exercises and Solutions

### Module 2 — Python (Sections 11–17)
- [x] Section 11 – Getting Started with Python
- [x] Section 12 – Python Collections for Data Engineering
- [x] Section 13 – Data Processing using Pandas (in progress)
- [ ] Section 14 – Project 1: File Format Converter
- [ ] Section 15 – Project 2: Files to Database Loader
- [ ] Section 16 – Troubleshooting and Debugging Python
- [ ] Section 17 – Performance Tuning of Python Applications

### Module 3 — Spark / PySpark (Sections 18–43)
- [ ] Section 18 – Getting Started with GCP
- [ ] Section 19 – Overview of Big Data and Data Lakes
- [ ] Section 20 – Overview of Spark and Spark Architecture
- [ ] Section 21 – Setup Databricks Environment
- [ ] Sections 22–32 – Spark SQL
- [ ] Sections 33–38 – PySpark DataFrame APIs
- [ ] Section 39 – ELT Data Pipelines using Databricks
- [ ] Sections 40–43 – Performance Tuning of Spark

### Module 4 — Hadoop and Production (Sections 44–53)
- [ ] Section 44 – Setup Hadoop and Spark Cluster using Dataproc
- [ ] Sections 45–47 – Linux, HDFS, and Hive
- [ ] Sections 48–53 – Spark SQL, PySpark, and Production Applications

---

## Commit Convention

```
Section <N> - <Brief description of what was added>

Examples:
  Section 6  - Add window functions and ranking SQL queries
  Section 13 - Add Pandas join and aggregation examples
  Section 22 - Add basic Spark SQL transformations
```

---

## How to Run

### SQL
```bash
psql -U your_user -d your_database -f sql/basic_queries/select_examples.sql
```

### Python
```bash
pip install pandas psycopg2
python python/pandas/filter_data.py
```

### PySpark
```bash
pip install pyspark
python spark/pyspark_df_apis/basic_transformations.py
```
