# SPortfolio Optimization using Modern Portfolio Theory

This project performs stock portfolio analysis using historical market data. 
It simulates thousands of portfolios and visualizes the Efficient Frontier 
to identify the portfolio with the optimal risk-return tradeoff.

## Features

- Download stock data using yfinance
- Calculate daily returns
- Analyze correlation between assets
- Simulate portfolios using Monte Carlo simulation
- Identify optimal portfolio using Sharpe Ratio
- Visualize the Efficient Frontier
- Calculate Value at Risk (VaR) for risk analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

## Concepts Used

- Portfolio Return
- Portfolio Volatility (Risk)
- Sharpe Ratio (Risk-adjusted return)
- Efficient Frontier
- Correlation Analysis

## Mathematical Background

Portfolio Return

```
Rp = wᵀ r
```

where  
w = vector of portfolio weights  
r = vector of asset returns  

Portfolio Variance

```
σ² = wᵀ Σ w
```

where  
Σ = covariance matrix of asset returns  

Sharpe Ratio

```
Sharpe = (Rp - Rf) / σp
```

where  
Rf = risk-free rate




