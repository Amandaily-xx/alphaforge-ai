# AlphaForge AI | PolyFinances Datathon 2026 :)

## About the Project

AlphaForge AI is an explainable investment screening prototype.

Our project focuses on Mateo, an investor with moderate risk tolerance, an 8–12-year investment horizon, and ESG preferences.

The tool combines historical market data with publicly documented ESG information to help users understand company-level financial risks and potential ESG concerns.

Rather than simply recommending investments, it provides a screening result with supporting evidence, explanations, and suggested next steps.

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

## Getting Started

Requires Python 3.10 or later.

1. **Clone the repository**
   ```bash
   git clone https://github.com/Amandaily-xx/alphaforge-ai.git
   cd alphaforge-ai
   ```

2. **Run the application**
   ```bash
   python agent.py --data data
   ```

3. **Open the demo**

   Visit http://127.0.0.1:8765 in your browser.

For the financial analysis notebook, install `pandas`, `numpy`, `matplotlib`, and `jupyter` separately.

## Initial Findings

Our first analysis covers November 2021 to November 2026.

- QQQ had the highest annualized return among the four ETFs, but also the highest volatility and largest maximum drawdown.
- ESGV had lower historical returns and higher volatility than SPY during this period.
- AGG had the lowest volatility, although it still experienced losses during the period.

These results show why investment decisions should not be based on returns alone.

We are continuing to explore how combining different assets may help balance growth and risk.

## Technologies Used

- **Python:** Financial calculations, data processing, and screening logic
- **pandas, NumPy, Matplotlib:** Exploratory data analysis and visualization
- **HTML, CSS, JavaScript:** Interactive demo interface
- **JSON:** ESG evidence and supporting records
- **GitHub:** Code sharing and team collaboration

## Limitations

Our analysis is based on historical data, which does not guarantee future performance.

Financial risk cannot be fully measured by volatility and drawdown alone. ESG screening also does not guarantee that a fund meets every investor's personal preferences.

This project is a competition prototype for educational purposes and does not provide personalized financial advice.
