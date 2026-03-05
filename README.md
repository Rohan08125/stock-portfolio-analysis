# Stock Portfolio Analysis

This project performs stock portfolio analysis using historical market data. 
It simulates thousands of portfolios and visualizes the Efficient Frontier 
to identify the portfolio with the optimal risk-return tradeoff.

## Features

- Download stock data using yfinance
- Calculate daily returns
- Plot stock price trends
- Compute correlation matrix
- Simulate random portfolios
- Find optimal portfolio using Sharpe Ratio
- Visualize Efficient Frontier

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

## Efficient Frontier Visualization

![Efficient Frontier](images/efficient_frontier.png)

## Project Structure

Stock_market_project
│
├── images
│   └── efficient_frontier.png
│
├── notebook
│   └── stock_analysis.ipynb
│
├── requirements.txt
└── README.md
## Run the Notebook

jupyter notebook notebook/stock_analysis.ipynb
