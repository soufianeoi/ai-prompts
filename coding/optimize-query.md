# Optimize a Database Query

**Category:** coding
**Model:** Any LLM
**Use case:** Improve slow database queries with indexing, rewriting, and analysis

## Prompt

Optimize this database query that's running slowly:

```sql
[Paste slow query here]
```

Database: [PostgreSQL / MySQL / SQLite / etc.]
Table size: [e.g., 5 million rows]
Current execution time: [e.g., 12 seconds]

Please provide:
1. Why it's slow (full scan, missing index, etc.)
2. Optimized query
3. Recommended indexes
4. Estimated improvement
5. Alternative approaches (caching, materialized views, etc.)

## Expected Output

Analysis of the bottleneck, optimized query, index recommendations, and alternative strategies.

## Tips

- Include EXPLAIN ANALYZE output if available
- Mention your database version
- Include table schemas (CREATE TABLE statements)
