# Project 1 – File Format Converter

A real-world Python project from **Section 14 – Project 1: File Format Converter** of the Udemy Data Engineering course.

## Project Overview
A Python utility that reads data files in one format and converts them to another — a core data ingestion task where files arrive in different formats and must be standardised for downstream processing.

## Supported Conversions
- CSV to JSON
- CSV to Parquet
- JSON to CSV
- JSON to Parquet

## Project Structure
```
file_format_converter/
├── app.py              # Main entry point
├── converter.py        # Core conversion logic
├── utils.py            # Helper functions
├── data/
│   ├── input/          # Sample input files
│   └── output/         # Converted output files
└── tests/
    └── test_converter.py
```

## How to Run
```bash
pip install pandas pyarrow
python app.py --input data/input/sample.csv --output data/output/sample.json --format json
```

## Key Concepts Practised
- File I/O with Pandas (read_csv, read_json, to_parquet)
- Command-line argument parsing with argparse
- Modular Python code organisation
- Error handling for invalid file formats

## Progress
- [ ] Section 14 – Project 1: File Format Converter (0/24 lectures)
