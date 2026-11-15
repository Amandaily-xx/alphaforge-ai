# AlphaForge AI | PolyFinances Datathon 2026 :)

## About the Project

Our goal is to build an AI-powered tool that helps investors better understand their investment choices based on their financial goals, risk tolerance, and personal preferences.

Different investors have different needs. An investment that works for someone looking for long-term growth may not be suitable for someone who wants to protect their savings.

We want our tool to consider these differences and explain its analysis using financial data, rather than simply recommending investments based on past returns.

## Our Approach

We are focusing on three main parts:

**1. Financial Data Analysis**

We use historical market data to understand how different assets have performed and how much risk they carry.

Our analysis includes:
- Historical returns
- Annualized volatility
- Maximum drawdown
- Correlation between assets

**2. Investor Profiles**

We use the investor profiles provided in the challenge to explore how investment decisions may change depending on each person's goals.

Our initial focus is Mateo, who wants to balance growth and stability while considering ESG (Environmental, Social, and Governance) preferences.

**3. AI Agent**

We plan to connect our financial analysis to an AI agent that can use the data to evaluate investments and explain the results.

The goal is to make the analysis clear, useful, and supported by evidence.

## Data

We use the AlphaForge starter dataset provided by the competition organizers (National Bank of Canada and AWS).

The dataset includes historical prices, asset information, exchange rates, economic indicators, and data source documentation.

For our initial analysis, we selected four ETFs:

| ETF | Description |
|---|---|
| ESGV | U.S. equity ETF with ESG screening |
| SPY | ETF tracking the S&P 500 |
| QQQ | ETF tracking the Nasdaq-100 |
| AGG | U.S. investment-grade bond ETF |

These ETFs allow us to compare different types of investments and study the relationship between return, risk, and diversification.

## Initial Findings

Our first analysis covers November 2021 to November 2026.

- QQQ had the highest annualized return among the four ETFs, but also the highest volatility and largest maximum drawdown.
- ESGV had lower historical returns and higher volatility than SPY during this period.
- AGG had the lowest volatility, although it still experienced losses during the period.

These results show why investment decisions should not be based on returns alone.

We are continuing to explore how combining different assets may help balance growth and risk.

## Tools

- Python
- pandas and NumPy
- Matplotlib
- Jupyter Notebook
- GitHub
- AWS (planned integration)

## Project Structure

```text
alphaforge-ai/
├── README.md
├── data/          # Starter financial datasets
├── analysis/      # EDA and financial risk analysis
├── agents/        # AI agent development
├── app/           # User interface
└── docs/          # Project documentation
```

## Limitations

Our analysis is based on historical data, which does not guarantee future performance.

Financial risk cannot be fully measured by volatility and drawdown alone. ESG screening also does not guarantee that a fund meets every investor's personal preferences.

This project is a competition prototype for educational purposes and does not provide personalized financial advice.
