# Data

This folder contains the starter financial datasets provided by the organizers of the PolyFinances Datathon 2026.

The datasets are used to analyze historical market performance, financial risk, and economic conditions for our AlphaForge AI project.

## Files

| File | Description |
|---|---|
| `assets_universe.csv` | List of available assets, including tickers, sectors, and asset classes |
| `prices_daily.csv` | Historical daily stock and ETF prices, trading volumes, and adjusted closing prices |
| `corporate_actions.csv` | Corporate actions such as dividends and stock splits |
| `fx_usdcad_daily.csv` | Historical USD/CAD exchange rates |
| `macro_rates.csv` | Macroeconomic indicators and interest rate data |
| `sources_metadata.csv` | Information about the original data sources |

## How We Use the Data

We use historical prices to calculate returns, volatility, and maximum drawdown, and to compare assets with market benchmarks.

Exchange rates allow us to express investment performance in Canadian dollars.

Our initial exploratory analysis is available in `analysis/financial_eda.ipynb`.

## Notes

Datasets are provided for the 2026 Datathon PolyFinances. Historical performance does not guarantee future results.
