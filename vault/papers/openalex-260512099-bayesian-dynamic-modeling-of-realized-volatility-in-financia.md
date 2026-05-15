---
# CSL-compatible fields
title: "Bayesian Dynamic Modeling of Realized Volatility in Financial Asset Price Forecasting"
author:
  - literal: "Patrick Woitschig"
  - literal: "Mike West"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12099"

# Custom fields
paper_id: "2605.12099"
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
processed_at: "2026-05-15T06:14:34Z"
created_at: "2026-05-15T06:14:34Z"
---

# Bayesian Dynamic Modeling of Realized Volatility in Financial Asset Price Forecasting

**Authors**: Patrick Woitschig, Mike West
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12099](https://arxiv.org/abs/2605.12099)

## Summary

This paper proposes a class of bivariate Bayesian dynamic models for joint price and realized volatility forecasting. By combining a dynamic gamma process for volatility with Bayesian dynamic linear models (DLMs) for price returns, the approach effectively captures leverage and feedback effects using high-frequency proxies. The method is computationally efficient, supporting real-time sequential filtering and forecasting, and demonstrates superior empirical performance in equity return predictions compared to traditional alternatives.

## Key Contributions

- Introduces a bivariate Bayesian dynamic model that integrates a dynamic gamma process for realized volatility with Bayesian dynamic linear models (DLMs) for asset returns.
- Provides a computationally efficient framework for sequential filtering, model monitoring, and forecasting that naturally incorporates leverage and feedback effects.
- Demonstrates significant improvements in equity return forecasting across S&P sector ETFs compared to standard benchmarks.

## Open Questions & Future Work

- [[adaptive-shape-index-rv-dlms]]
- [[multivariate-extension-rv-dlms]]

## Archivist Review

The paper introduces a well-defined bivariate Bayesian dynamic modeling framework. The proposed open questions are high-quality, addressing significant theoretical and practical bottlenecks (adaptive precision modeling and high-dimensional scaling) consistent with the long-term goals of the vault. No new concepts were approved as the core method is a specialized application of existing Bayesian DLM structures and gamma processes, which are already well-represented in the literature.

### Approved Open Questions
- Adaptive shape index for RV-DLMs: This addresses the fundamental limitation of static precision modeling in high-frequency financial econometrics, where data quality is inherently non-stationary.
- Multivariate extension for RV-DLMs: Transitioning to multivariate frameworks is essential for applying these dynamic models to realistic financial tasks like risk-parity or large-scale portfolio construction.

## Links

- [Abstract](https://arxiv.org/abs/2605.12099)
- [PDF](https://arxiv.org/pdf/2605.12099)

