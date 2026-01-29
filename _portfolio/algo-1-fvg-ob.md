---
title: "FVG-OB Algorithmic Trading Strategy"
excerpt: "Fair Value Gap and Order Block detection system using Lumibot with live trading integration"
collection: portfolio
category: algo-trading
---

## Overview

Developed and optimized an algorithmic trading strategy based on Fair Value Gap (FVG) and Order Block (OB) detection — concepts from Smart Money / ICT trading methodology.

## Strategy Logic

**Fair Value Gaps (FVG):**
- Identifies price imbalances where a candle's range doesn't overlap with candles two positions away
- These gaps often act as magnets for price to revisit

**Order Blocks (OB):**
- Detects institutional accumulation/distribution zones
- Last opposing candle before a strong directional move

## Implementation

- **Framework:** Lumibot for backtesting and live trading
- **Data:** Polygon.io for historical and real-time market data
- **Broker:** Alpaca for paper and live trading execution
- **Assets:** QQQ options and SPY

## Features

- Multi-timeframe analysis (daily for bias, hourly for entry)
- Dynamic position sizing based on volatility
- Risk management with automatic stop-loss and take-profit
- Real-time monitoring dashboard

## Technical Stack

Python, Lumibot, Polygon API, Alpaca API, Pandas, NumPy
