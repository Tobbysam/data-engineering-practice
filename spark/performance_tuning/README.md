# Spark Performance Tuning

Scripts from **Sections 40–43** of the Udemy Data Engineering course, covering Spark performance optimisation.

## Topics Covered

| Section | Topic |
|---------|-------|
| Section 40 | Catalyst Optimizer – how Spark plans query execution |
| Section 41 | Cluster Configuration – driver, executor, memory, cores |
| Section 42 | Performance tuning when inferring schema from CSV/JSON |
| Section 43 | Columnar file formats (Parquet, ORC) and partitioning strategy |

## Files in This Folder
| File | Description |
|------|-------------|
| `catalyst_optimizer.py` | Reading Spark explain plans |
| `cluster_config.py` | Setting executor memory, cores, parallelism |
| `schema_inference.py` | Why schema inference is slow and how to fix it |
| `parquet_partitioning.py` | Writing partitioned Parquet, partition pruning |
| `broadcast_joins.py` | Using broadcast hints for small-table joins |

## Key Concepts
- **Catalyst Optimizer**: Use `df.explain(True)` to see the physical plan
- **Columnar Formats**: Parquet enables predicate pushdown and compression
- **Partitioning**: Only read relevant partitions instead of the full dataset

## Progress
- [ ] Section 40 – Catalyst Optimizer (0/10 lectures)
- [ ] Section 41 – Cluster Configuration (0/11 lectures)
- [ ] Section 42 – Schema Inference Tuning (0/5 lectures)
- [ ] Section 43 – Columnar Formats and Partitioning (0/18 lectures)
