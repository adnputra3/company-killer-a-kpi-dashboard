README.md
KPI Dashboard

A lightweight business KPI dashboard built with **Python, Streamlit, Pandas, Plotly, and DuckDB**.
This project tracks core metrics (Revenue, Orders, Avg Order Value, Customers) and visualizes trends for quick decision-making.

## Features

- KPI cards for key business metrics
- Revenue trend chart over time
- Orders trend chart over time
- Revenue breakdown by category
- Recent data table preview
- Simple local dataset for quick demo/testing

## Tech Stack

- Python 3
- Streamlit
- Pandas
- Plotly
- DuckDB

## Project Structure

```bash
A-kpi-dashboard/
├── app.py
└── data/
└── sales.csv
Run Locally
python3 -m venv .venv
source .venv/bin/activate
pip install pandas plotly streamlit duckdb
streamlit run app.py
Open: http://localhost:8501

Why I Built This
This is part of my Company Killer portfolio track:

A) KPI Dashboard
B) Internal Company Tool
C) AI Analyst Assistant
Goal: build practical, business-ready automation and analytics tools that reduce manual work and improve reporting speed.

Next Improvements
Date filters and category filters
CSV upload support
Weekly/monthly KPI comparison
Authentication + multi-user support
Cloud deployment + live demo link
