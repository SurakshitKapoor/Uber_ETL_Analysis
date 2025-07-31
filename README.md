# 🚖 Uber ETL & SQL Analysis with DuckDB
This is the data engineering project of uber transactions.

This project demonstrates a complete ETL (Extract, Transform, Load) pipeline using real Uber trip data, followed by SQL-based analysis and visualizations using DuckDB and Python.


## 📁 Project Overview
We performed a professional data engineering exercise using Python and DuckDB.

## ✅ ETL Steps:
**Extract**: Loaded raw trip data from a CSV file.

**Transform**: Cleaned and structured the data, then created dimensional models (fact_table, datetime, passenger_count, rate_code, payment_type).

**Load**: Stored the transformed data into DuckDB, which acts as a lightweight local data warehouse.


## 🧠 SQL Analysis
Used pure SQL queries on DuckDB via Python to extract insights like:

1. Average trip distance by rate code
2. Daily trip counts
3. Trip counts by passenger count
4. Payment type distribution


## 📊 Visualization
Created data visualizations using Matplotlib to support analytical findings.


## 🛠️ Tech Stack
1. Python (Pandas, Matplotlib)
2. DuckDB
3. Jupyter Notebook


## 📦 How to Run
Clone the repo or download the notebook

Install requirements: _pip install duckdb pandas matplotlib_

Run the notebook step by step

Modify queries or visualizations as needed

## 💾 Output
1. SQL-based data insights
2. Visual charts
3. Final transformed data saved as .csv and .duckdb
