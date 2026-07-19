# Python Performance Tuning

Scripts from **Section 17 – Performance Tuning of Python Applications** of the Udemy Data Engineering course.

## Topics Covered (Section 17)
- Profiling Python code with cProfile and timeit
- Optimising loops and data transformations
- Generator functions vs. list comprehensions for memory efficiency
- Efficient file I/O patterns
- Vectorised operations with Pandas (avoiding row-by-row iteration)
- Parallel processing with multiprocessing and concurrent.futures

## Files in This Folder
| File | Description |
|------|-------------|
| `profiling.py` | Using cProfile and timeit |
| `generators.py` | Generator patterns for large datasets |
| `vectorised_ops.py` | Pandas vectorisation vs iterrows |
| `parallel_processing.py` | Multiprocessing examples |

## Key Rules
- Never use iterrows() in Pandas for large DataFrames — use vectorised operations
- Use generators for memory-efficient processing of large files
- Profile before optimising — don't guess at bottlenecks

## Progress
- [ ] Section 17 – Performance Tuning of Python Applications (0/18 lectures)
