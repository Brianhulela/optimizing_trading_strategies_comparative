# Optimizing Moving Average Strategies with Genetic Algorithms

This repository contains all the code used in the article **“How I Used Genetic Algorithms to Tune a Simple Trading Strategy on the S&P 500”** published on Medium.

The project explores how to apply a genetic algorithm to optimize a simple double moving average crossover strategy using historical S&P 500 data from 1990 to 2024. The goal is to evolve the best combination of short- and long-term moving average windows that maximize final portfolio value on training data, then evaluate the strategy’s performance on unseen data.

## What You'll Find in This Repository

- Historical data fetching and preprocessing using `yfinance`
- Backtesting logic for a double moving average crossover strategy
- Genetic algorithm implementation using the `deap` library
- Visualization of buy/sell signals, equity curves, and monthly return patterns
- Output artifacts: strategy plots and performance summary
