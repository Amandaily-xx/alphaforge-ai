# Financial Data Analysis

This folder contains our initial financial analysis for the AlphaForge AI project.

## Objective

We explored historical ETF performance and risk to better understand how different investments may fit different investor profiles.

Our initial focus is Mateo, who wants to balance growth and stability while considering ESG preferences.

## Data and Methods

We used the AlphaForge starter dataset provided by the Datathon organizers, covering November 2021 to November 2026.

We first checked the data for missing values and duplicate records. We then selected four ETFs:

- **ESGV:** U.S. equity ETF with ESG screening
- **SPY:** S&P 500 ETF
- **QQQ:** Nasdaq-100 ETF
- **AGG:** U.S. bond ETF

Using Python, pandas, NumPy, and Matplotlib, we calculated annualized historical returns, annualized volatility, maximum drawdown, and correlations between daily ETF returns.

## Main Findings

**1. QQQ had the highest return, but also the highest risk.**

QQQ had an annualized return of 12.49%, volatility of 23.36%, and maximum drawdown of 35.12%.

**2. ESG screening does not necessarily mean lower financial risk.**

ESGV had slightly higher volatility than SPY (18.72% vs. 17.33%) during our analysis period.

**3. The equity ETFs were highly correlated.**

ESGV and SPY had a correlation of 0.99, while ESGV and QQQ had a correlation of 0.96. This suggests that combining these ETFs may provide limited additional diversification.

**4. AGG may provide diversification benefits.**

ESGV and AGG had a much lower correlation of 0.23. This suggests that combining stocks and bonds could help reduce overall portfolio volatility.


## Limitations

Our analysis is based on historical data and does not predict future performance.

Correlations can change over time, and lower volatility does not mean an investment is risk-free.

ESG screening also does not guarantee that a fund matches every investor's preferences.

## Files

- `financial_eda.ipynb` — Data exploration, ETF performance, risk metrics, and correlation analysis.

The original datasets are stored in the repository's `data/` folder.
