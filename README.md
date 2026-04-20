ACC102 Mini Assignment | Track 2: GitHub Data Analysis Project

This project evaluates the risk and return performance of three major U.S. technology stocks — Apple (AAPL), Microsoft (MSFT), and NVIDIA (NVDA) — from 2020 to 2025. The analysis focuses on cumulative returns, annualized returns, volatility, and maximum drawdown, aiming to provide investors with a clear comparison of their growth potential and risk profiles.

1. Project Purpose

The primary goal is to conduct a comparative risk-return analysis of three leading tech giants, highlighting the trade-off between performance and risk. By examining metrics such as volatility and maximum drawdown, this project helps users understand the risk-adjusted performance of growth-oriented versus more stable tech stocks, supporting more informed investment decisions.

2. Data Source

• Data platform: CRSP (via WRDS)

• Frequency: Monthly

• Sample period: 2020–2025

• Data construction: Merged crsp.msf (monthly prices and returns) and crsp.msfhdr (ticker mapping) using a left join to preserve all valid observations.

3. Python Methods Used

The analysis leverages a complete Python-based workflow:

• Data cleaning & preprocessing with pandas (handling missing values, correcting prices, sorting by date/ticker)

• Cumulative return calculation using groupby and transform

• Key risk metrics: Annualized return, annualized volatility, and maximum drawdown

• Visualization: Cumulative return line charts with matplotlib

• Output: Cleaned dataset and performance metrics exported to Excel for review.

4. Key Outputs

• Cumulative return comparison chart

• Risk-return performance summary table

• Cleaned monthly stock dataset (Excel)

• Full analysis code in Jupyter Notebook

5. Main Insights

• NVIDIA delivered the highest cumulative return over the period, driven by the AI boom and GPU demand.

• Apple and Microsoft showed steadier, more consistent growth with significantly lower volatility and smaller drawdowns.

• Risk and return are strongly correlated: NVIDIA’s superior performance came with substantially higher risk.

• Risk-adjusted performance is stronger for Apple and Microsoft, making them more suitable for long-term, risk-averse investors.

6. How to Run

1. Open the provided .ipynb notebook in Jupyter or VS Code.

2. Execute all cells sequentially to reproduce the analysis.

3. Review the cumulative return plot, risk metrics table, and exported Excel files.

7. Limitations & Future Improvements

• Sample size: Only three tech stocks are included, limiting generalizability to the broader market.

• Frequency: Monthly data does not capture intraday volatility or short-term price movements.

• Scope: The analysis excludes dividends, transaction costs, and systematic risk factors.

• Improvements: Expand to S&P 500 constituents, include dividend reinvestment, and incorporate Fama-French factor models for more robust risk-adjusted performance evaluation
