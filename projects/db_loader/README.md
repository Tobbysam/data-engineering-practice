# Project 2 – Files to Database Loader

A real-world Python project from **Section 15 – Project 2: Files to Database Loader** of the Udemy Data Engineering course.

## Project Overview
A Python pipeline that reads structured data files (CSV, JSON) and loads them into a PostgreSQL database — a core ELT pattern in data engineering.

## Project Structure
```
db_loader/
├── app.py              # Main entry point
├── loader.py           # Core DB loading logic
├── db_connection.py    # PostgreSQL connection setup
├── utils.py            # File reading helpers
├── data/
│   └── input/          # Sample CSV/JSON files to load
└── tests/
    └── test_loader.py
```

## How to Run
```bash
pip install pandas psycopg2-binary sqlalchemy
python app.py --file data/input/orders.csv --table orders
```

## Key Concepts Practised
- Connecting to PostgreSQL using psycopg2 and SQLAlchemy
- Using Pandas to_sql() to write DataFrames to a database table
- Handling schema creation and upserts
- Logging pipeline execution status
- Environment variables for database credentials

## Progress
- [ ] Section 15 – Project 2: Files to Database Loader (0/7 lectures)
