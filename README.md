# NVDA Volatility Predictability via PCA

This repo contains a small research project that builds an aggregate volatility “state” factor for NVDA using daily OHLC data and tests whether volatility is mean-reverting.

For full details (math, implementation, and results), see the notebook:
- `NVDA_Vol_PCA_Minimal_repo.ipynb`

## What’s included
- the full analysis notebook (recommended entry point)
- NVDA daily OHLC CSV used for the notebook
- saved figures and tables produced by the notebook

## Quick start
1) Open `NVDA_Vol_PCA_Minimal_repo.ipynb` in JupyterLab / VS Code / Google Colab
2) Run cells top to bottom

## Environment
pip install pandas numpy scikit-learn matplotlib statsmodels
