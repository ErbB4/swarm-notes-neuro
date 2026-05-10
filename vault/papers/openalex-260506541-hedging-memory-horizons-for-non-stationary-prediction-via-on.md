---
# CSL-compatible fields
title: "Hedging Memory Horizons for Non-Stationary Prediction via Online Aggregation"
author:
  - literal: "Yutong Wang"
  - literal: "Yannig Goude"
  - literal: "Qiwei Yao"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06541"

# Custom fields
paper_id: "2605.06541"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "melo-memory-hedged-aggregation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:05:07Z"
created_at: "2026-05-10T06:05:07Z"
---

# Hedging Memory Horizons for Non-Stationary Prediction via Online Aggregation

**Authors**: Yutong Wang, Yannig Goude, Qiwei Yao
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06541](https://arxiv.org/abs/2605.06541)

## Summary

This paper introduces MELO, a model-agnostic online aggregation framework designed for non-stationary prediction where the optimal memory horizon is unknown. By wrapping base predictors with exponentially weighted least-squares (EWLS) experts across varying forgetting factors and utilizing the MLpol aggregation rule, MELO effectively balances stability and rapid adaptation. The method is validated on challenging real-world electricity-load forecasting, demonstrating superior performance over baselines even in the absence of exogenous regime-specific information.

## Key Contributions

- Proposes MELO, a model-agnostic aggregation framework that wraps base predictors with EWLS-adapted experts at varying forgetting factors to handle unknown distribution shifts.
- Establishes deterministic oracle inequalities proving that MELO tracks the best time-varying affine combinations of base predictors with sublinear regret.
- Demonstrates 34.7% RMSE reduction on French electricity-load forecasting during the COVID-19 regime shift without explicit policy covariates or regime markers.

## Open Questions & Future Work

- [[memory-hedging-extension-directions]]

## Key Concepts

- [[melo-memory-hedged-aggregation]]: A model-agnostic online aggregation framework that hedges across multiple adaptation scales using EWLS-adapted forecasts to maintain stability and adapt to distribution shifts.

## Archivist Review

MELO represents a significant, reusable contribution to online forecasting under distribution shift by formalizing the hedging of memory horizons. The open question identifies clear, high-impact avenues for future research into multivariate and structured loss extensions. No datasets were approved as they were not presented as novel, unique, or central enough to the specific claims of this paper to warrant a standalone record.

### Approved Concepts
- Memory-hedged Exponentially Weighted Least-Squares Online aggregation (MELO): MELO introduces a novel model-agnostic framework for online prediction under distribution shift by dynamically aggregating forecasts across multiple forgetting factors without needing external regime markers.

### Approved Open Questions
- Extensions for memory-hedged aggregation: These extensions would significantly broaden the applicability of online aggregation frameworks to real-world operational environments where targets are multivariate, retraining pipelines are dynamic, and loss functions reflect complex decision costs.

## Links

- [Abstract](https://arxiv.org/abs/2605.06541)
- [PDF](https://arxiv.org/pdf/2605.06541)

