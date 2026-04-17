---
# CSL-compatible fields
title: "Forecasting Oil Prices Across the Distribution: A Quantile VAR Approach"
author:
  - literal: "Hilde C. Bjornland"
  - literal: "Nicolás Hardy"
  - literal: "Dimitris Korobilis"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12927"

# Custom fields
paper_id: "2604.12927"
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
processed_at: "2026-04-17T05:45:46Z"
created_at: "2026-04-17T05:45:46Z"
---

# Forecasting Oil Prices Across the Distribution: A Quantile VAR Approach

**Authors**: Hilde C. Bjornland, Nicolás Hardy, Dimitris Korobilis
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12927](https://arxiv.org/abs/2604.12927)

## Summary

This paper introduces a Quantile Bayesian Vector Autoregression (QBVAR) to model oil prices across the full conditional distribution. By allowing predictor effects to vary by quantile, the model captures asymmetries that traditional mean-focused approaches fail to account for. Evaluation using monthly data from 1975 to 2025 demonstrates significant gains in both median point prediction and left-tail risk assessment compared to standard Bayesian VARs. The results highlight the importance of quantile-specific dynamics for better understanding market uncertainty and risk during oil price volatility.

## Key Contributions

- Introduces a Quantile Bayesian Vector Autoregression (QBVAR) to capture quantile-specific predictor dynamics for oil price forecasting.
- Demonstrates that QBVAR improves median point forecast accuracy by 2-5% over standard Bayesian VAR models.
- Shows that the QBVAR provides 10-25% improvement in left-tail risk forecasting, specifically during crisis periods, while highlighting the difficulty of right-tail prediction.

## Open Questions & Future Work

- [[right-tail-forecast-asymmetry-bottleneck]]

## Archivist Review

I reviewed the Quantile Bayesian VAR approach, which applies existing econometric techniques to oil price forecasting. I decided against creating a concept note for QBVAR as it is a standard extension of established statistical methodology. I approved the open question regarding right-tail forecasting, as it frames a non-trivial, persistent challenge in conditional distribution modeling that is broadly relevant to time-series forecasting research.

### Approved Open Questions
- Right-Tail Forecast Asymmetry Bottleneck: This is a fundamental limitation in conditional distribution forecasting, highlighting the trade-off between modeling tail-specific dependencies and the stochastic nature of volatile upside events.

### Rejected Candidates
- [concept] Quantile Bayesian Vector Autoregression (QBVAR) (`qbvar`) - not_novel: Quantile variants of VAR models are standard econometric methodology and not a novel machine learning framework worth a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.12927)
- [PDF](https://arxiv.org/pdf/2604.12927)

