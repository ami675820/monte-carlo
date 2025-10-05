# Portfolio Risk Analysis using Monte Carlo Simulation

This project provides a comprehensive financial modeling tool in Python for analyzing portfolio risk and performance. It leverages a Monte Carlo simulation framework to forecast potential portfolio outcomes, optimize asset allocation, and calculate key risk metrics such as Value at Risk (VaR), Conditional VaR (CVaR), and Max Drawdown.

The analysis is demonstrated using the top 10 stocks from the Nifty 50 index, making it particularly relevant for investors in the Indian stock market.

## Features

* **Automated Data Acquisition**: Fetches historical stock data directly from Yahoo Finance using the `yfinance` library.
* **Portfolio Optimization**: Utilizes a Monte Carlo simulation to find the optimal asset weights that maximize the Sharpe Ratio (risk-adjusted return).
* **Risk Metrics Calculation**: Calculates and visualizes key risk metrics, including:
    * **Value at Risk (VaR)**: The maximum expected loss at a given confidence level.
    * **Conditional VaR (CVaR)**: The expected loss if the VaR threshold is breached.
    * **Maximum Drawdown**: The largest peak-to-trough decline in portfolio value.
* **Multiple Simulation Methods**:
    * **Parametric Simulation**: Assumes that asset returns follow a normal distribution.
    * **Historical Bootstrapping**: A non-parametric method that samples directly from historical returns, making no assumptions about the return distribution.
* **Stress Testing**: Includes a scenario for stress-testing the portfolio's resilience to a sudden market shock.
* **Professional Visualization**: Generates clear and informative plots to visualize portfolio distributions and the efficient frontier.

## Getting Started

### Prerequisites

You will need Python installed on your system. The code relies on the following Python libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `yfinance`

You can install all the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib yfinance
