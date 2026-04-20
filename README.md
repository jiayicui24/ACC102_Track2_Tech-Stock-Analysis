# Tech Stock Risk-Return Analysis (2020–2025)
ACC102 Mini Assignment | Track 2: GitHub Data Analysis Project

## 1. Project Purpose
This project analyzes the long-term performance of three major U.S. tech giants: Apple (AAPL), Microsoft (MSFT), and NVIDIA (NVDA). It focuses on **risk-adjusted returns, cumulative returns, volatility, and maximum drawdown** to help investors make data-driven decisions.

## 2. Data Source
- Data platform: WRDS / CRSP
- Period: 2020–2025 (monthly frequency)
- Data merged: crsp.msf + crsp.msfhdr (via LEFT JOIN)

## 3. Python Methods Used
- Data cleaning & preprocessing (pandas)
- Cumulative return calculation
- Annualized return & volatility
- Maximum drawdown computation
- Visualization (matplotlib)
- Excel output for results

## 4. Key Outputs
- Cumulative return comparison chart
- Risk-return performance table
- Cleaned stock dataset (Excel)

## 5. Main Insights
- NVIDIA achieved the **highest cumulative return** driven by the AI boom.
- Apple and Microsoft showed **stronger stability and better risk-adjusted performance**.
- Risk and return are highly correlated: higher return comes with higher volatility.

## 6. How to Run
1. Open the `.ipynb` notebook
2. Run all cells to reproduce analysis
3. View charts and exported results

## 7. Limitations & Improvements
- Only three large-cap tech stocks included
- Monthly data (no intraday information)
- Dividends and transaction costs not included
- Future expansion: S&P 500 stocks + factor models
