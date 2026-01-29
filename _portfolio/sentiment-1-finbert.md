---
title: "FinBERT Sentiment Alpha Strategy"
excerpt: "Sentiment-based trading strategy achieving 14.5% annualized alpha using NLP on 330,000+ financial headlines"
collection: portfolio
category: sentiment-analysis
---

## Overview

Built a systematic trading strategy using FinBERT (a BERT model fine-tuned for financial sentiment) to analyze 330,000+ financial headlines from 2009-2020.

## Methodology

- **Data:** 330,000+ financial news headlines (2009-2020)
- **Model:** FinBERT for sentiment classification (positive/negative/neutral)
- **Signal Generation:** Aggregated daily sentiment scores to generate trading signals
- **Validation:** Information Coefficient (IC) analysis to measure predictive power

## Factor Attribution

Performed Fama-French factor attribution to isolate alpha from common risk factors:
- Market (MKT)
- Size (SMB)
- Value (HML)
- Momentum (MOM)

## Results

- **14.5% annualized alpha** before transaction costs
- Statistically significant Information Coefficient
- Robust performance across different market regimes

## Technical Stack

Python, PyTorch, FinBERT, Pandas, Statsmodels, Matplotlib

## Key Learnings

- NLP sentiment signals have meaningful predictive power for short-term returns
- Proper factor attribution is essential to validate true alpha
- Transaction costs significantly impact strategy viability at high frequencies
