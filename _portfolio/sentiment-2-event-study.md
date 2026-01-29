---
title: "Event Study: Earnings Sentiment Impact"
excerpt: "Analyzing market reactions to earnings announcements using sentiment analysis and event study methodology"
collection: portfolio
permalink: /portfolio/sentiment-2-event-study/
---

## Overview

Applied event study methodology combined with NLP sentiment analysis to measure how earnings announcement sentiment affects abnormal returns.

## Methodology

**Event Study Framework:**
- Event window: [-5, +5] days around earnings announcements
- Estimation window: [-250, -30] days for expected return model
- Abnormal returns calculated using market model

**Sentiment Analysis:**
- Analyzed earnings call transcripts and press releases
- Classified tone as positive/negative/neutral
- Measured sentiment surprise (actual vs. expected tone)

## Data

- Earnings announcements from S&P 500 companies
- Corresponding earnings call transcripts
- Daily price data for abnormal return calculation

## Findings

- Positive sentiment surprise → Positive CAR (Cumulative Abnormal Return)
- Effect persists for 2-3 days post-announcement
- Stronger effect for smaller companies with less analyst coverage

## Technical Stack

Python, FinBERT, Pandas, Statsmodels, WRDS/CRSP data

## Academic Framework

Follows standard event study methodology from finance literature (MacKinlay, 1997).
