# Retail Data & Visualisation (SQLite + Python)

Recreates my coursework: build a retail SQLite database from CSVs, run analytical SQL queries, and plot insights (purchases per customer, monthly revenue, top products, by-country revenue).

## What this shows
- ETL: create DB, schema, load CSVs from a zip, clean with pandas
- Analytics: SQL queries for KPIs (customers, monthly trends, top products, by country)
- Visuals: bar/line/pie charts with clear labels and titles

## How to run
1. `pip install -r requirements.txt`
2. Open `notebooks/main.ipynb` and run all cells to: build DB → run queries → plot charts.

## Repo map
- `src/retaildb.py` — DB + schema + load  
- `src/queries.py` — analytics SQL  
- `src/visuals.py` — plots  
- `notebooks/main.ipynb` — end-to-end demo

