# Comparative Analysis of Trading Strategy Optimization Methods

This project investigates which parameter optimization method yields the best results when tuning a simple trading strategy — the Double Moving Average Crossover — using historical S&P 500 data.

We compared the following optimization techniques:

- Grid Search
- Random Search
- Bayesian Optimization
- Genetic Algorithm

Each method was evaluated on three key criteria:

- Final strategy return on unseen test data
- Number of trades executed
- Average runtime per optimization run

## Strategy Setup

We used the S&P 500 index (`^GSPC`) from January 1990 to December 2024.

- Training period: 1990-01-01 to 2019-12-31
- Testing period: 2020-01-01 to 2024-12-31

The strategy used two tunable parameters:

- Short moving average window
- Long moving average window

The goal was to optimize these parameters to maximize the final portfolio value on the test set.

## Summary

This repository contains the analysis, visualizations, and results comparing all four optimization methods. The best-performing approach delivered higher returns than buy and hold, while also minimizing trade frequency and reducing runtime.

To read the full write-up, see the article on Medium [insert link].
