---
title: "PokerBench"
excerpt: "Benchmarking LLM decision-making in poker scenarios with expected value analysis"
collection: portfolio
category: for-fun
---

## Overview

A project exploring how well large language models (LLMs) can make decisions in poker scenarios, testing their ability to calculate expected value and make optimal plays.

## Motivation

Poker is an interesting testbed for AI decision-making because it involves:
- Incomplete information
- Probabilistic reasoning
- Expected value calculations
- Game theory concepts

## Methodology

**Test Scenarios:**
- Pre-flop decisions (call, raise, fold)
- Post-flop bet sizing
- Pot odds calculations
- Implied odds reasoning

**Evaluation:**
- Compared LLM decisions against GTO (Game Theory Optimal) solutions
- Measured EV loss from suboptimal decisions
- Tested various prompt engineering approaches

## Findings

- LLMs struggle with precise pot odds calculations
- Better at qualitative reasoning (hand strength, position)
- Chain-of-thought prompting improved accuracy
- Still far from GTO play in complex spots

## Technical Stack

Python, OpenAI API, PokerStove (for equity calculations)

## Future Work

- Fine-tuning on poker hand histories
- Testing against poker solver outputs
- Multi-street scenario analysis
