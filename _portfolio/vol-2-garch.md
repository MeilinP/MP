---
title: "Volatility Forecasting with GARCH Models"
excerpt: "Time-series volatility modeling using GARCH family models for risk management and trading"
collection: portfolio
permalink: /portfolio/vol-2-garch/
---

## Overview

Implemented GARCH (Generalized Autoregressive Conditional Heteroskedasticity) family models to forecast volatility for risk management and options trading applications.

## Models Implemented

**GARCH(1,1):**
- Standard model capturing volatility clustering
- σ²ₜ = ω + α·ε²ₜ₋₁ + β·σ²ₜ₋₁

**EGARCH:**
- Exponential GARCH for asymmetric volatility response
- Captures leverage effect (negative returns → higher volatility)

**GJR-GARCH:**
- Threshold model for asymmetric shocks
- Different response to positive vs. negative returns

## Applications

**Risk Management:**
- Value at Risk (VaR) calculation
- Expected Shortfall estimation
- Dynamic position sizing

**Options Trading:**
- Volatility forecasts vs. implied volatility
- Identifying mispriced options
- Volatility term structure analysis

## Evaluation

- Out-of-sample forecasting performance
- Compared against realized volatility
- Model selection using AIC/BIC

## Results

- EGARCH captured leverage effect best for equity indices
- 1-day ahead forecasts showed significant predictive power
- Useful for identifying volatility regime changes

## Technical Stack

Python, arch package, Statsmodels, Pandas, Matplotlib

## Key Learnings

- Volatility clustering is persistent and predictable
- Asymmetric models better capture equity market dynamics
- Forecast horizon matters for model selection
