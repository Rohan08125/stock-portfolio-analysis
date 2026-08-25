# Modern Portfolio Optimization & Risk Analysis

This project analyzes and optimizes a multi-asset portfolio using historical market data and Monte Carlo simulation. It combines Modern Portfolio Theory with quantitative risk measures to identify an optimal risk-return portfolio and evaluate its downside risk.

## Features

- Download historical market data using yfinance
- Calculate daily asset returns
- Analyze asset correlations
- Calculate annualized covariance matrix
- Simulate 1,000 random portfolios using Monte Carlo simulation
- Optimize portfolio selection using Sharpe Ratio
- Visualize portfolio risk-return distribution
- Analyze optimal portfolio allocation
- Calculate 95% Historical Value at Risk (VaR)
- Calculate 95% Expected Shortfall (CVaR)
- Calculate maximum portfolio drawdown
- Visualize portfolio growth and drawdown

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance
- Jupyter Notebook

## Assets Analyzed

- AAPL
- MSFT
- GOOGL
- TSLA
- SPY
- GLD
- TLT

## Quantitative Finance Concepts

- Modern Portfolio Theory
- Portfolio Return
- Portfolio Volatility
- Covariance Matrix
- Correlation Analysis
- Sharpe Ratio
- Monte Carlo Simulation
- Risk-Return Analysis
- Value at Risk (VaR)
- Expected Shortfall (CVaR)
- Maximum Drawdown
- Portfolio Diversification

## Methodology

### Portfolio Return

```text
Rp = wᵀr
```

where:

- `w` = vector of portfolio weights
- `r` = vector of asset returns

### Portfolio Variance

```text
σ²p = wᵀΣw
```

where:

- `Σ` = covariance matrix of asset returns

### Sharpe Ratio

```text
Sharpe = (Rp - Rf) / σp
```

where:

- `Rp` = portfolio return
- `Rf` = risk-free rate
- `σp` = portfolio volatility

## Results

The Monte Carlo simulation identified an optimal portfolio with:

- **Annualized Return:** 37.94%
- **Annualized Volatility:** 28.13%
- **Sharpe Ratio:** 1.21
- **95% Historical VaR:** 2.73%
- **95% Expected Shortfall:** 4.09%
- **Maximum Drawdown:** 37.43%

## Project Structure

```text
Stock_market_project/
│
├── notebook/
│   └── stock_analysis.ipynb
│
└── requirements.txt
```

## Disclaimer

This project is for educational and research purposes only and does not constitute financial advice or an investment recommendation.
