---
# CSL-compatible fields
title: "Yield Curve Forecasting using Machine Learning and Econometrics: A Comparative Analysis"
author:
  - literal: "Aman Singh"
  - literal: "Tokunbo Ogunfunmi"
  - literal: "Sanjiv Das"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.09842"

# Custom fields
paper_id: "2605.09842"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "econometrics"
  - "financial-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:10Z"
created_at: "2026-05-14T06:09:10Z"
---

# Yield Curve Forecasting using Machine Learning and Econometrics: A Comparative Analysis

**Authors**: Aman Singh, Tokunbo Ogunfunmi, Sanjiv Das
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.09842](https://arxiv.org/abs/2605.09842)

## Summary

This paper evaluates the efficacy of machine learning and deep learning models against traditional econometric methods for forecasting U.S. Treasury yield curves. Using 47 years of daily financial data, the study finds that classical models such as ARIMA remain highly competitive, often outperforming modern neural architectures. The analysis also identifies TimeGPT, LGBM, and RNNs as the most effective machine learning approaches among those tested. Finally, the authors investigate the sensitivity of deep learning models to the stationarity of input data, offering practical insights for financial time-series forecasting.

## Key Contributions

- Conducts a comprehensive comparative study of classical econometrics (ARIMA), machine learning (LGBM), and deep learning (RNNs, TimeGPT) on 47 years of daily U.S. Treasury yield curve data.
- Demonstrates that classical econometric models like ARIMA and naive benchmarks frequently outperform complex deep learning architectures in yield curve forecasting.
- Provides empirical evidence on the impact of data stationarity versus nonstationarity as inputs for deep learning-based yield curve forecasting.

## Open Questions & Future Work

- [[yield-curve-forecasting-ml-econometrics-bottleneck]]

## Archivist Review

The paper provides a standard comparative analysis between established econometric models and modern machine learning/deep learning approaches in the financial domain. No new fundamental concepts or reusable mechanisms were introduced, as the findings confirm existing industry consensus on the robustness of simpler models. I have formulated a more focused open question centered on the performance gap bottleneck between ML and econometrics in this specific domain.

### Approved Open Questions
- ML-Econometric Yield Forecasting Bottleneck: The persistent performance gap suggests that standard deep learning architectures lack necessary inductive biases for financial yield curve data, necessitating a move toward exogenous integration and rigorous probabilistic frameworks.

### Rejected Candidates
- [open_question] Yield Curve Forecasting Improvements (`yield-curve-forecasting-model-limitations`) - other: The candidate is too broad and describes a list of disparate empirical next steps rather than a singular, well-defined research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.09842)
- [PDF](https://arxiv.org/pdf/2605.09842)

