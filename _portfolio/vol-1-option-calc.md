---
title: "Option Price Calculator"
excerpt: "Black-Scholes and binomial tree option pricing with Greeks visualization"
collection: portfolio
category: volatility
---

## Overview

Built an interactive option pricing calculator implementing multiple pricing models with real-time Greeks calculation and visualization.

## Pricing Models

**Black-Scholes Model:**
- European call and put options
- Closed-form solution for fast computation
- Assumptions: constant volatility, no dividends, log-normal returns

**Binomial Tree Model:**
- American and European options
- Handles early exercise for American options
- Configurable number of steps for accuracy

## Greeks Calculation

Real-time computation of option sensitivities:
- **Delta (Δ):** Price sensitivity to underlying
- **Gamma (Γ):** Delta sensitivity to underlying
- **Theta (Θ):** Time decay
- **Vega (ν):** Volatility sensitivity
- **Rho (ρ):** Interest rate sensitivity

## Features

- Interactive sliders for input parameters
- 3D surface plots for price vs. spot and volatility
- Greeks heatmaps across strike/expiry grid
- P&L visualization for various strategies

## Technical Stack

Python, NumPy, SciPy, Plotly, Streamlit

## Applications

- Understanding option pricing dynamics
- Strategy analysis before trade execution
- Educational tool for learning derivatives
