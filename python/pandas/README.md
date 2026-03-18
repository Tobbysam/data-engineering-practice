# Pandas for Data Engineering

Scripts from **Section 13 – Data Processing using Pandas DataFrame APIs** of the Udemy Data Engineering course.

## Topics Covered (Section 13)
- Reading CSV files into DataFrames
- Filtering rows with query() and boolean indexing
- Aggregations: groupby(), count(), sum(), mean()
- Multi-column groupby (group by month AND status)
- DataFrame joins: merge() for inner, left, right joins
- Sorting with sort_values()
- Writing DataFrames to CSV, JSON, Parquet

## Files in This Folder
| File | Description |
|------|-------------|
| `read_csv.py` | Reading CSV data into Pandas DataFrames |
| `filter_data.py` | Filtering rows with query() |
| `group_by.py` | COUNT by status and by month/status |
| `joins.py` | Inner join between two DataFrames |
| `aggregations.py` | Aggregations on join results |
| `sort_data.py` | Sorting DataFrames |
| `write_to_json.py` | Writing DataFrames to JSON files |
| `dynamic_columns.py` | Creating DataFrames with a dynamic column list |

## How to Run
```bash
pip install pandas
python read_csv.py
python joins.py
```

## Progress
- [x] Section 13 – Data Processing using Pandas (8/12 lectures – in progress)
