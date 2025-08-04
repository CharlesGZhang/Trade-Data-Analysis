# Trade-Data-Analysis
Analysis of a stock trader's trade data

This project analyzes and visualizes a dataset of personal stock trades to identify trends, evaluate performance, and assess risk-adjusted returns using metrics like Sharpe Ratio. It groups trades by:
- Trade Term (Short vs Long)
- Share Price Bins (< $50, $50–149, ≥ $150)
- Both Trade Term and Share Price

# Features
- Cleans and preprocesses trade history (filled symbols, removed header rows)

- Groups trades by:
  - Term (Short/Long)
  - Share Price bin
  - Lot selection strategy

- Computes:
  - Average gain per group
  - Sharpe ratio per group
  - Cumulative return over time
- Visualizations:
  - Bar charts of average gains and Sharpe ratios
  - Gain/loss outcome distributions
  - Actual vs. predicted return plot from ML model

- Basic ML model to predict trade return using:
  - Trade type (symbol)
  - Trade frequency
  - Trade size

# Insights
The insights I had for the trader consisted of leaning into their strengths. There was a very obvious discrepancy between types of trades, with more expensive and longer-term trades having a direct correlation with higher Sharpe Ratios. As I continue to monitor this trader's trades, I hope to uncover more insights to help increase returns.
