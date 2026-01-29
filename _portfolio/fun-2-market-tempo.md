---
title: "Market Tempo: Jazz Patterns in Financial Markets"
excerpt: "Exploring correlations between Charlie Parker's jazz rhythms and SPY price movements using Dynamic Time Warping"
collection: portfolio
permalink: /portfolio/fun-2-market-tempo/
---

## Overview

An unconventional research project investigating whether temporal patterns in jazz music correlate with intraday price movements in SPY (S&P 500 ETF).

## Hypothesis

Musical improvisation and market price action both exhibit complex temporal patterns. This project explores whether rhythm patterns from Charlie Parker's bebop solos share structural similarities with market microstructure.

## Methodology

- **Audio Analysis:** Extracted onset times and rhythm patterns from Charlie Parker recordings
- **Market Data:** Intraday SPY price data at 1-minute resolution
- **Pattern Matching:** Dynamic Time Warping (DTW) to measure similarity between rhythm sequences and price movement sequences
- **Prediction:** Used pattern matches to forecast 60-minute price direction

## Results

- **72% accuracy** for 60-minute directional predictions
- Identified recurring "tempo signatures" that preceded specific market behaviors
- Found statistically significant correlations in high-volatility periods

## Technical Stack

Python, Librosa (audio analysis), FastDTW, Pandas, Scikit-learn

## Why This Project?

Sometimes the most interesting insights come from unexpected connections. This project was an exercise in:
- Creative hypothesis generation
- Cross-domain signal processing
- Keeping curiosity alive in quantitative work

## Disclaimer

This is an exploratory/fun project — not investment advice!
