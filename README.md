# PoW vs PoS: Bitcoin–Ethereum Trend & ARIMA Forecasting

This repository contains datasets and code for analyzing Bitcoin and Ethereum under PoW, and forecasting key metrics (transactions, hash rate, energy consumption) using ARIMA.

## Contents
- `data/raw/` original sources (CSV/JSON)
- `data/processed/` cleaned & resampled daily series
- `notebooks/` end-to-end analysis (preprocess, trends, ARIMA)
- `src/` reusable scripts (preprocessing, ARIMA training, metrics)
- `results/` figures & tables for the manuscript
- `paper/` LaTeX manuscript & figures

## Quickstart
```bash
python -m venv .venv
source .venv/bin/activate   # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
jupyter notebook
