Quantitative Market Risk Engine

A Python-based quantitative risk analysis project that measures portfolio risk using Value at Risk (VaR), Expected Shortfall (ES), backtesting, Monte Carlo simulation, and historical stress testing.

The project applies quantitative finance concepts to a multi-asset portfolio using historical market data.

Features

* Historical VaR: Estimates potential portfolio losses using historical returns.
* Parametric VaR: Estimates risk using statistical assumptions about portfolio returns.
* Monte Carlo VaR: Simulates potential portfolio outcomes to estimate downside risk.
* Expected Shortfall (ES): Estimates the average loss beyond the VaR threshold.
* VaR Backtesting: Evaluates model performance by comparing predicted risk against realized portfolio losses.
* Stress Testing: Examines portfolio performance under adverse historical market conditions.

Portfolio

The engine analyzes a portfolio consisting of the following ETFs:

Ticker	Asset Class / Exposure	Weight
SPY	US equities	30%
QQQ	Nasdaq-100 equities	20%
TLT	Long-term US Treasury bonds	20%
GLD	Gold	15%
XLE	Energy equities	15%

Data period: January 2015 – January 2026

Historical price data is obtained using Python’s yfinance library.

Technologies

* Python
* NumPy
* pandas
* Matplotlib
* yfinance
* Jupyter Notebook

Methodology

The project follows a quantitative risk management workflow:

1. Retrieve and explore historical market prices.
2. Calculate asset returns and portfolio returns.
3. Estimate portfolio VaR using multiple approaches.
4. Calculate Expected Shortfall to assess tail risk.
5. Backtest VaR estimates against realized losses.
6. Apply historical stress scenarios to examine portfolio vulnerabilities.

Disclaimer

This project is for educational and research purposes only. Its risk estimates depend on historical data, modeling assumptions, and portfolio construction choices. They should not be interpreted as investment advice or guarantees of future performance.


