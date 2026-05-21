---
# CSL-compatible fields
title: "Sequential Structure in Intraday Futures Data: LSTM vs Gradient Boosting on MNQ"
author:
  - literal: "Mathias Mesfin"
issued:
  date-parts:
    - [2026, 5, 18]
url: "https://arxiv.org/abs/2605.17724"

# Custom fields
paper_id: "2605.17724"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-21T06:28:08Z"
created_at: "2026-05-21T06:28:08Z"
---

# Sequential Structure in Intraday Futures Data: LSTM vs Gradient Boosting on MNQ

**Authors**: Mathias Mesfin
**Date**: 2026-05-18
**Paper ID**: [openalex:2605.17724](https://arxiv.org/abs/2605.17724)

## Summary

This paper investigates the viability of using LSTM and gradient boosting models for intraday directional prediction of Micro E-Mini Nasdaq 100 (MNQ) futures. By training on four years of 5-minute OHLCV data using a strict expanding-window validation framework, the study evaluates whether sequential structure can be reliably learned from this scale of financial data. Results show that no configuration performs significantly better than the base rate, with permutation tests failing to reject the null hypothesis of no predictive edge. The study concludes that current sequential ML approaches, including those inspired by foundation models like Kronos, struggle to extract stable signals from isolated, medium-scale financial datasets.

## Key Contributions

- Evaluates LSTM and gradient boosting performance on Micro E-Mini Nasdaq 100 (MNQ) 5-minute OHLCV data across 944 trading days.
- Demonstrates that none of the tested configurations achieve statistically significant predictive accuracy above the base rate using expanding-window walk-forward validation.
- Establishes an empirical lower bound on data requirements for sequential machine learning in financial forecasting by showing four years of single-instrument data are insufficient for capturing exploitable intraday structure.

## Links

- [Abstract](https://arxiv.org/abs/2605.17724)
- [PDF](https://arxiv.org/pdf/2605.17724)

