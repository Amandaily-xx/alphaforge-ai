# Financial Data Analysis

This folder contains our initial financial analysis for the AlphaForge AI project.

## Objective

We explored the historical performance and risk of different ETFs to better understand how investment choices may fit different investor profiles.

Our initial focus is Mateo, who wants to balance growth and stability while considering ESG preferences.

The goal of this analysis is to provide useful financial data that can support our AI agent's investment explanations.

## Data and Methods

We used the financial datasets provided by the Datathon organizers, covering November 2021 to November 2026.

We started by checking missing values, duplicate records, and the available assets.

We then selected four ETFs:

- **ESGV:** U.S. equity ETF with ESG screening
- **SPY:** S&P 500 ETF
- **QQQ:** Nasdaq-100 ETF
- **AGG:** U.S. bond ETF

Using Python, pandas, NumPy, and Matplotlib, we calculated:

- Annualized historical returns
- Annualized volatility
- Maximum drawdown
- Correlations between daily ETF returns

We also compared hypothetical portfolios with different allocations between ESGV and AGG.

## Main Findings

**1. Higher returns came with higher risk in our sample.**

QQQ had the highest annualized return (12.49%), but also the highest volatility (23.36%) and largest maximum drawdown (35.12%).

**2. ESG screening does not necessarily mean lower financial risk.**

ESGV had an annualized return of 10.09% and volatility of 18.72%, compared with 11.68% and 17.33% for SPY.

**3. Equity ETFs moved very similarly.**

ESGV and SPY had a correlation of 0.99, while ESGV and QQQ had a correlation of 0.96. Combining highly correlated ETFs may provide limited additional diversification.

**4. Bonds may help with diversification.**

ESGV and AGG had a much lower correlation of 0.23. This suggests that combining equity and bond exposure could help reduce portfolio volatility.

## How This Supports Our AI Agent

These results provide a starting point for evaluating investments based on an investor's goals and risk tolerance.

For Mateo, the analysis helps us explore the trade-off between growth and stability.

The AI agent can use these findings to explain investment risks and compare different options, rather than focusing only on historical returns.

## Limitations

This analysis uses historical data and does not predict future market performance.

Correlation can change over time, and lower volatility does not mean an investment is risk-free.

ESGV follows an ESG screening approach, but additional information is needed to check whether an investment fully matches Mateo's preferences.

## Files

- `financial_eda.ipynb` — Data exploration, risk metrics, correlation analysis, and portfolio comparison.

The starter datasets are stored in the `data/` folder of the main repository.
