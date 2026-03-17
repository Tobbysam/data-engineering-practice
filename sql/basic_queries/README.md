# Basic SQL Queries

SQL practice files from **Section 5 – Writing Basic SQL Queries** of the Udemy Data Engineering course.

## Topics Covered (Section 5)
- SELECT statements and column aliases
- WHERE clause filtering with conditions
- ORDER BY for sorting results
- Aggregate functions: COUNT, SUM, AVG, MIN, MAX
- GROUP BY and HAVING for grouped aggregations
- INNER JOIN, LEFT JOIN, RIGHT JOIN
- Subqueries and nested SELECT

## Files in This Folder
| File | Description |
|------|-------------|
| `select_basics.sql` | Basic SELECT and column filtering |
| `where_filtering.sql` | Filtering rows with WHERE conditions |
| `aggregations.sql` | GROUP BY, HAVING, COUNT, SUM, AVG |
| `joins.sql` | INNER, LEFT, RIGHT JOIN examples |
| `order_by.sql` | Sorting query results |
| `subqueries.sql` | Nested queries and subquery patterns |

## Database Setup
These queries run against the application tables set up in **Section 4** using PostgreSQL.

```bash
psql -U your_user -d your_db -f select_basics.sql
```

## Progress
- [x] Section 5 – Basic SQL Queries (14/15 lectures completed)
