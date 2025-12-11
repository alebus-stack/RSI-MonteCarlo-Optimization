# Multi-Asset Systematic Strategy 
**Algorithmic trading strategy using the Relative Strength Index (RSI) and Simple Moving Average (SMA), optimized with Monte Carlo simulations and validated via rigorous walk-forward analysis.**
This project provides a comprehensive Python framework for:
- Fetching historical financial data (using yfinance).
- Backtesting a customizable RSI-based mean-reversion or momentum strategy.
- Realistic execution modelling: slippage, latency, transaction costs, and partial-fill simulation.
- Integrated stop-loss logic and Kelly Criterion position sizing.
- Robust parameter optimization using **Monte Carlo** techniques to find optimal RSI entry/exit thresholds.
- Out-of-sample validation through **walk-forward analysis** to prevent overfitting.
- Generating detailed performance metrics (Sharpe Ratio, Max Drawdown) and visualizations (equity curves, trade timelines).
