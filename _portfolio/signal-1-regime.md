---
title: "Market Regime Identifier for SPY"
excerpt: "Multi-timeframe market regime detection system for systematic trading decisions"
collection: portfolio
permalink: /portfolio/signal-1-regime/
---

## Overview

Built a market regime classification system that identifies different market states (trending, mean-reverting, high volatility) to inform trading strategy selection.

## Methodology

**Features Extracted:**
- Price momentum across multiple timeframes
- Volatility measures (realized vol, ATR, Bollinger Band width)
- Volume patterns and anomalies
- Technical indicator divergences

**Regime Classification:**
- Trending Bull / Trending Bear
- Range-bound / Mean-reverting
- High volatility / Low volatility
- Breakout conditions

## Multi-Timeframe Analysis

- **Daily:** Overall market bias and regime
- **Hourly:** Entry timing and confirmation
- **15-min:** Fine-tuned execution

## Application

The regime identifier feeds into strategy selection:
- Trending regimes → Momentum strategies
- Range-bound → Mean reversion strategies
- High volatility → Reduced position sizing or sideline

## Technical Stack

Python, Pandas, Scikit-learn, Lumibot, Polygon API

## Results

Improved strategy performance by avoiding trades during unfavorable regimes.
