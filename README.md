# Project1
Advance Time series Forecasting with Deep Learning and attention Mechanisms
# Advanced Time Series Forecasting — Transformer with Attention

**Author:** Luca  
**Project:** Transformer-based multivariate time series forecasting with attention.

## Goals
- Generate or ingest a multivariate dataset (≥3 correlated features + time index).
- Train a Transformer model to forecast next H steps from previous L steps.
- Compare against a statistical baseline (ARIMA/Prophet or naive) using MAE, RMSE, MAPE.
- Visualize learned attention weights and interpret forecasting errors.

## Quick start (local)
1. Create environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
