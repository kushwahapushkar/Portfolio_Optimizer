# Portfolio_Optimizer
Portfolio Optimization Tool: Built in Python using Modern Portfolio Theory to optimize stock portfolios. Fetches live data via Yahoo Finance, computes risk-return metrics, maximizes Sharpe ratio, and visualizes the efficient frontier with optimal asset allocations.


Portfolio Optimization Tool
Overview

This project implements Modern Portfolio Theory (Markowitz Optimization) to construct an optimal stock portfolio. It fetches real stock data using Yahoo Finance, calculates daily/annualized returns and risks, and applies mean-variance optimization to maximize the Sharpe ratio. The tool also visualizes the Efficient Frontier and highlights the optimal portfolio with recommended asset allocations.

Features

Fetches stock/ETF data automatically using yfinance

Computes returns, volatility, and covariance matrix

Uses scipy.optimize to maximize Sharpe ratio with constraints

Visualizes Efficient Frontier (risk vs return tradeoff)

Highlights the optimal portfolio on the frontier plot

Prints expected return, volatility, and asset weights

Tech Stack

Python

pandas, numpy → Data handling

yfinance → Stock data

scipy.optimize → Optimization

matplotlib → Visualization

Getting Started
1. Clone Repository
git clone https://github.com/your-username/portfolio-optimization.git
cd portfolio-optimization

2. Install Dependencies
pip install -r requirements.txt

3. Run Script
python portfolio_optimizer.py

Example Output

Optimal Weights

AAPL : 25%
MSFT : 30%
GOOGL: 20%
AMZN : 25%


Performance Metrics

Expected Annual Return: 18.2%
Annual Volatility: 14.5%
Sharpe Ratio: 0.97


Efficient Frontier Plot

Efficient frontier curve with the optimal portfolio marked by a red star.

Scope of Improvements

This is the basic version — here are future improvements that can be added:

User Input Dashboard – Build a Streamlit app to allow users to enter tickers, time periods, and constraints.

More Constraints – Add options like maximum allocation per stock, sector-level limits, or short-selling.

Multiple Strategies – Implement risk parity, equal-weight, and Black-Litterman models for comparison.

Dynamic Data – Automate with live data refresh and rolling-window optimization.

Visualization Upgrade – Use Plotly/Dash for interactive frontier and allocation charts.

<img width="970" height="647" alt="image" src="https://github.com/user-attachments/assets/6f515d06-183c-4c23-beed-31b086680020" />

