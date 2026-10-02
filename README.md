# Supply Chain Analyst App

A browser-based tool for inventory analytics. No installation needed: open `index.html`.

## Features
- ABC (Pareto) classification of SKUs
- EOQ, safety stock (service level, demand and lead-time variability) and reorder point
- Demand forecasting (moving average, exponential smoothing) with MAPE
- Upload a CSV or paste data directly

## Data format
CSV columns: `date, sku, units, unit_cost` (date as YYYY-MM-DD). See `sample_sales.csv`.

## Run
Open `index.html` in a browser, or host it free with GitHub Pages (Settings > Pages > Deploy from branch > main).

## Note
The built-in "sample data" and `sample_sales.csv` are synthetic and for demonstration only.
