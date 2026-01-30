---
title: "FinBERT Sentiment Alpha Strategy"
excerpt: "Built sentiment signal achieving **0.71% daily IC**, **15% annualized alpha** (t=2.73), and **Sharpe 1.26** using NLP on 330K+ financial headlines"
collection: portfolio
permalink: /portfolio/sentiment-1-finbert/
---

## Overview

Built a sentiment-based trading strategy using FinBERT (a BERT model fine-tuned for financial sentiment) to analyze 330,000+ financial headlines from S&P 500 stocks (2009-2020).

**[📓 View Full Notebook on Google Colab](https://colab.research.google.com/drive/1dtA9E8c91v3ZmXNQKlLcIzxOAxW9HL_t)** | **[GitHub Repo](https://github.com/MeilinP/FinBERT_Sentiment_Analysis_on_SP500Constitutes)**

## Key Results

| Metric | Value |
|--------|-------|
| Information Coefficient | 0.71% daily |
| Fama-French Alpha | 15% annualized (t=2.73) |
| Best Strategy Sharpe | 1.26 |
| Dataset | 328K headlines, 384 stocks |

## Methodology

- **Data:** 330,000+ financial news headlines (2009-2020)
- - **Model:** FinBERT for sentiment classification (positive/negative/neutral)
  - - **Signal Generation:** Aggregated daily sentiment scores to generate trading signals
    - - **Validation:** Information Coefficient (IC) analysis to measure predictive power
     
      - ## Factor Attribution
     
      - Performed Fama-French factor attribution to isolate alpha from common risk factors:
      - - Market (MKT)
        - - Size (SMB)
          - - Value (HML)
           
            - Result: **15% annualized alpha with t-statistic of 2.73** — statistically significant after controlling for standard factors.
           
            - ## Strategy Optimization
           
            - Tested multiple configurations to find optimal parameters:
            - - **Rebalancing frequency:** Daily vs. weekly vs. monthly
              - - **News volume filters:** Minimum 3, 4, 5, 6+ headlines per stock
               
                - **Finding:** Weekly rebalancing with 5+ news filter produced the best risk-adjusted returns (Sharpe 1.26).
               
                - ## Tech Stack
               
                - - **NLP:** FinBERT (HuggingFace Transformers)
                  - - **Data:** pandas, numpy, yfinance
                    - - **Compute:** PyTorch with GPU acceleration (Google Colab T4)
                      - - **Statistics:** statsmodels for Fama-French regression
