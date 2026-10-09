# Tesla & GameStop — Stock & Revenue Dashboard

Interactive dashboard analyzing historical share prices and revenues for Tesla (TSLA) and GameStop (GME).

Rebuilt hands-on as part of the IBM Data Analyst Professional Certificate — *Python Project for Data Science*.

## What it does

1. **Extracts stock data** via the `yfinance` API (full history: Open, High, Low, Close, Volume)
2. **Scrapes revenue data** from the web with `requests` + `BeautifulSoup`
3. **Cleans** the scraped revenue figures (strips `$` and `,` so values become numeric)
4. **Visualizes** everything in an interactive Plotly dashboard (share price + revenue)

## Try it

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Pdrsmth/tesla-gamestop-stock-dashboard/blob/main/IBM_Tesla_GameStop_Dashboard.ipynb)

## Tech

Python · pandas · yfinance · BeautifulSoup · Plotly

## File

- `IBM_Tesla_GameStop_Dashboard.ipynb` — the full analysis, start to finish
