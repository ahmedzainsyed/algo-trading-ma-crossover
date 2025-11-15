# Moving Average Crossover Trading Bot  
### Developed by: **Syed Zain Ahmed**

This project implements a complete **algorithmic trading system** using a 50/200 Moving Average Crossover strategy with robust **risk management**, a custom **backtesting engine**, and a **synthetic OHLCV data generator**.  
The entire system runs inside a **Google Colab notebook**, making it portable, reproducible, and beginner-friendly.

---

## Features

### Strategy  
- 50/200 Moving Average Crossover  
- Buy when short MA crosses above long MA  
- Exit when short MA crosses below long MA  
- ATR-based stop-loss (2 × ATR)

### Risk Management  
- 1% risk per trade  
- Maximum 3% portfolio exposure  
- Dynamic position sizing  
- 15% maximum drawdown stop  
- Commission + slippage modeled  
- Capital tracking across the entire backtest  

### Backtesting Engine  
- Step-by-step trade simulation  
- Equity curve generation  
- Trade logs stored in DataFrame  
- Automatic drawdown detection  
- Clean OOP-modular architecture  
- Safe execution with index alignment fixes

### Synthetic Data Generator  
Generates realistic OHLCV data using:  
- Geometric Brownian Motion  
- Business-day calendar  
- Randomized volatility and drift  
- 753 trading days (2023–2025)

---

## Notebook

Main notebook file in the repository

