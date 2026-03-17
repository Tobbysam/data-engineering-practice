# SQL Troubleshooting and Debugging

SQL practice files from **Section 7 – SQL Troubleshooting and Debugging Guide** of the Udemy Data Engineering course.

## Topics Covered (Section 7)
- Identifying and fixing common SQL syntax errors
- Debugging incorrect query results
- Understanding NULL handling and edge cases
- Fixing data type mismatch issues
- Troubleshooting JOIN problems and cartesian products
- Using EXPLAIN / EXPLAIN ANALYZE to understand query plans

## Files in This Folder
| File | Description |
|------|-------------|
| `null_handling.sql` | NULL comparisons, COALESCE, NULLIF |
| `join_issues.sql` | Diagnosing incorrect join results |
| `data_type_fixes.sql` | Casting and type conversion |
| `explain_analyze.sql` | Reading query execution plans |

## Key Debugging Techniques
- Always use EXPLAIN ANALYZE before optimising a slow query
- Check for implicit type conversions preventing index use
- Watch out for NULLs in WHERE conditions and JOINs

## Progress
- [ ] Section 7 – SQL Troubleshooting and Debugging (0/15 lectures)
