# GIM – Greeks in the Machine  
*An Exploratory Framework for Options Sentiment, Forecasting, and Market Microstructure*

---

## Overview

Greeks in the Machine (GIM) is an applied research initiative that explores the dynamics of options markets using a combination of sentiment analysis, time-series forecasting, and custom Python/R tooling. It serves as both a testing ground for development and a portfolio of exploratory methods applied to real market data.

This project reflects my growth in:
- Translating complex financial theory into applied code
- Navigating multi-modal datasets (options chains, FRED time series, time and sales logs)
- Building modular, extensible tools for data-driven decision support

In Greek mythology, Mnemosyne is the personification of memory and mother of the Muses. This system embodies that metaphor—functioning as a memory keeper that empowers deeper insight, creativity, and conceptual continuity.

---

## Structure

GIM is divided into three functional components:

### 1. **Monte Carlo Simulations**
  - Developed as part of my early progression in Python and R
  - Models outcome distributions under variable volatility and strike conditions
  - Used to train intuition around derivatives behavior and path dependency

📁 [`MonteCarlo_Simulations`](./MonteCarlo_Simulations/README.md)

### 2. **ARIMA Liquidity Forecasting**
  - Applies ARIMA-based forecasting models to macroeconomic indicators (e.g., M2, Treasury yield spreads)
  - Data sourced from the Federal Reserve Economic Data (FRED) API
  - Aims to identify signals related to systemic liquidity cycles and equity market stress conditions

📁 [`ARIMA_Liquidity_Forecast`](./ARIMA_Liquidity_Forecast/README.md)

---

### 3. **Options Time & Sales Sentiment Tool**
  - Parses raw time and sales data across options chains
  - Aggregates open interest changes across strike prices (Cumulative Strike-Level Open Interest)
  - Designed to enhance visibility into sentiment concentration, momentum shifts, and potential inflection points

📁 [`TimeAndSales_CumulativeOI`](./TimeAndSales_CumulativeOI/README.md)

---

## Technical Stack

- **Languages**: Python, R
- **Libraries**: pandas, NumPy, matplotlib, statsmodels, yfinance, FRED API
- **Workflow Tools**: Jupyter Notebooks, GitHub, Virtual Environments

---

## Reflections

This project embodies my evolving interest in **quantitative strategy**, **derivatives data analysis**, and **custom market tooling**. While not production-grade, the methods and explorations documented here reflect a deliberate focus on:

- Modeling real uncertainty, not just historical fit
- Identifying microstructure signals outside conventional charting
- Learning by building—from scratch, in context, with purpose
