# S&P 500 Moving Average Strategy with Bayesian Optimization

This folder contains the code and experiment artifacts for a trading strategy based on double moving average crossovers, optimized using Bayesian Optimization.

The strategy is tested on historical S&P 500 data spanning several decades and aims to outperform a traditional buy-and-hold approach. The optimization process explores different combinations of short- and long-term moving average windows to maximize final portfolio value on a training set, then evaluates performance on an out-of-sample test set.

Visualizations, strategy metrics, and monthly performance breakdowns are included to help interpret the behavior of the strategy over time.

All analysis is done in Python using open-source libraries such as `pandas`, `yfinance`, `matplotlib`, and `bayesian-optimization`.

---
