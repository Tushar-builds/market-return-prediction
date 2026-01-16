# Market Return Prediction Model

This project focuses on predicting next-day market direction using historical
price and volume data. The goal is to explore whether simple, interpretable
features can provide predictive signal under realistic market assumptions.

## Problem Statement
Given historical OHLCV data, predict whether the next trading day's return
will be positive or negative.

## Data
- Historical OHLCV market data
- Returns computed from closing prices
- Rolling volatility and volume-based features

## Feature Engineering
- Lagged returns
- Rolling volatility
- Volume-based indicators

## Model
- Classification-based approach
- Baseline models (Logistic Regression / similar)

## Evaluation
- Accuracy on held-out data
- Emphasis on avoiding look-ahead bias
- Discussion on robustness and generalization

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
