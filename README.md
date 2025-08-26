# 📦 SQL Data Warehouse Project

This repo is where I’m building and experimenting with a mini data warehouse pipeline. The idea is to take raw CSV data, move it through different stages, and end up with a clean star schema ready for analytics.

I’m following along with Data With Baraa’s project, but I’m making it my own by exploring each step, breaking things down, and keeping notes here.

🚀 What this project covers

1. Data modeling – designing a star schema for fact and dimension tables.
2. Data loading (ETL) – using SQL to stage raw CSV files, transform them, and insert into warehouse tables.
3. SQL querying – running analytical queries on top of the warehouse to test how everything fits together.
4. Data warehouse concepts – understanding how raw data gets shaped into something that supports business reporting.

🗂️ Project Structure

```
data/ → contains the raw CSV files (like customers, orders, products).
staging/ → staging tables used for cleaning and preparing data.
warehouse/ → star schema tables (fact + dimensions).
queries/ → example SQL queries for analysis.
```

🔑 Key Learnings (for me)

1. Difference between staging tables and warehouse tables.
2. Why star schema is preferred for analytics.
3. How to write SQL transformations that make messy data usable.
4. The actual flow from raw → staging → warehouse → insights.

---
📖 Resources

1. Tutorial Video
2. Original Repo by DataWithBaraa
