# GIM – Greeks in the Machine
*An exploratory research line in options positioning, open-interest analytics, and macro liquidity forecasting*

---

## Overview

Greeks in the Machine (GIM) is an ongoing personal research line exploring options-market data — time and sales, open interest, and options positioning — alongside macro liquidity indicators, using custom Python and R tooling.

This work reflects ongoing development in:
- Translating options and market-structure concepts into applied code
- Working with multi-modal datasets (options chains, FRED macro time series, time-and-sales logs)
- Building modular, reusable analysis tooling

## Status

This project line is in active cleanup — the underlying tools (a cumulative open-interest tool, an ARIMA/FRED macro-liquidity forecaster, and Monte Carlo derivatives simulations) exist and run, but are being rebuilt against public or synthetic sample data before publication, since the originals were developed against personal brokerage exports that can't be shared publicly. Published components will be linked here as they're ready.

## Technical Stack

- **Languages**: Python, R
- **Libraries**: pandas, NumPy, matplotlib, statsmodels, yfinance, FRED API
- **Workflow Tools**: Jupyter Notebooks, Git, virtual environments
