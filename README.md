# Amazon Products Sales Analysis Dashboard

A Streamlit + Plotly recreation of the supplied Amazon Products sales dashboard screenshot.

## Features
- KPI cards for YTD sales, QTD sales, products sold, and reviews
- Monthly sales line chart and weekly sales column chart
- Product-category sales table
- Top 5 products by YTD sales and by YTD reviews
- Sidebar category and quarter filters
- Dark dashboard styling

## Requirements
- Python 3.9+
- See `requirements.txt`

## Run locally
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

pip install -r requirements.txt
streamlit run app.py
```

## Data
CSV files are in `data/`. They are illustrative sample data recreated from the visible figures in the screenshot, not the original underlying dataset. Replace them with your real data while keeping the same column names.

## Project structure
```text
amazon_sales_dashboard/
├── app.py
├── requirements.txt
├── README.md
└── data/
    ├── category_sales.csv
    ├── monthly_sales.csv
    ├── weekly_sales.csv
    ├── top_products_sales.csv
    └── top_products_reviews.csv
```
