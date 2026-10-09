# Tesla and GameStop Stock & Revenue Analysis

Python notebook comparing historical share prices and quarterly revenue for Tesla and GameStop. The project combines API-based market data, web-scraped revenue tables, data cleaning and time-series visualization.

This notebook was completed as part of the IBM Data Analyst Professional Certificate and is presented here as a reproducible portfolio project.

## Project workflow

1. Download historical stock prices with `yfinance`.
2. Extract quarterly revenue tables from web pages.
3. Clean date and revenue fields with pandas.
4. Remove missing and invalid values.
5. Visualize share-price and revenue trends for each company.

## Questions explored

- How did Tesla and GameStop share prices change over time?
- How did quarterly revenue develop during the same periods?
- What differences are visible when market prices and company revenue are viewed together?

## Technologies

- Python
- pandas
- yfinance
- Requests and Beautiful Soup
- Matplotlib
- Jupyter Notebook

## Repository structure

- `Revenue Data and Building a Dashboard-v1.ipynb` — data extraction, cleaning and visualizations
- `requirements.txt` — Python dependencies

## Running the notebook

```bash
python -m venv .venv
```

Activate the environment, then install the dependencies:

```bash
pip install -r requirements.txt
jupyter notebook
```

Open the notebook and run the cells in order. Internet access is required because the project retrieves stock and revenue data from external sources.

## Limitations

- Results depend on the availability and structure of external data sources.
- Historical market prices and revenue alone are not sufficient to value a company.
- This project is educational and is not financial advice.

