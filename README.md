# Quant Trading Backtester

A Python-based backtesting project for evaluating quantitative trading strategies on historical market data.

## Overview
This project implements a simple moving average crossover strategy and compares its performance against a buy-and-hold benchmark.

## Features
- Historical market data download with Yahoo Finance
- Moving average crossover signal generation
- Buy/sell signal visualization
- Strategy return calculation
- Buy-and-hold comparison
- Performance metrics:
  - annualized return
  - volatility
  - Sharpe ratio
  - maximum drawdown

## Technologies
- Python
- pandas
- numpy
- matplotlib
- yfinance

## Strategy Logic
The strategy generates:
- a **buy signal** when the short-term moving average rises above the long-term moving average
- a **sell signal** when the short-term moving average falls below the long-term moving average

## Example Output
The notebook produces:
- stock price chart with buy/sell signals
- cumulative return comparison
- portfolio value comparison
- summary performance statistics

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Install dependencies
3. Run all cells
4. Change the ticker symbol and date range to test different assets

## Note
This project is intended for educational purposes and does not constitute financial advice.
