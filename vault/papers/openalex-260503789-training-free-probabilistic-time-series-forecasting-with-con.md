---
# CSL-compatible fields
title: "Training-Free Probabilistic Time-Series Forecasting with Conformal Seasonal Pools"
author:
  - literal: "Valery Manokhin"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03789"

# Custom fields
paper_id: "2605.03789"
paper_source: "openalex"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "time-series-forecasting"
  - "conformal-prediction"
  - "calibration"
architectures:
  []
datasets:
  []
concept_slugs:
  - "conformal-seasonal-pools"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:43:23Z"
created_at: "2026-05-08T05:43:23Z"
---

# Training-Free Probabilistic Time-Series Forecasting with Conformal Seasonal Pools

**Authors**: Valery Manokhin
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03789](https://arxiv.org/abs/2605.03789)

## Summary

This paper introduces Conformal Seasonal Pools (CSP), a training-free, non-parametric probabilistic forecasting framework that enhances reliability in safety-critical applications. By combining empirical observations from matching seasonal periods with historical residuals, the method avoids the calibration pitfalls common in deep learning-based models, such as systematic under-coverage. Empirical results across six benchmark datasets show that CSP provides superior predictive intervals and computational efficiency compared to deep non-parametric alternatives. The author argues that such training-free conformal methods should serve as mandatory baselines for evaluating learned time-series models.

## Key Contributions

- Introduces Conformal Seasonal Pools (CSP), a training-free probabilistic forecasting framework that generates predictions by mixing historical seasonal empirical draws with signed residuals around a seasonal naive baseline.
- Demonstrates significant performance improvements over DeepNPTS across six standard benchmarks (electricity, exchange_rate, solar_energy, taxi, traffic, wikipedia) in terms of CRPS, normalized mean quantile loss, and empirical coverage.
- Achieves superior calibration (mean coverage 0.89 vs 0.66) while running 500x faster than deep learning baselines, highlighting the critical failure of parametric models in safety-sensitive forecasting tasks.

## Open Questions & Future Work

- [[conformal-time-series-coverage-guarantees]]

## Key Concepts

- [[conformal-seasonal-pools]]: A training-free probabilistic forecasting method that generates prediction intervals by combining seasonal empirical observations with historical residuals.

## Archivist Review

The paper introduces a highly effective training-free forecasting mechanism, Conformal Seasonal Pools, which challenges the assumption that deep learning models are necessary for high-quality probabilistic forecasting. I have approved this as a key concept for the vault. I also approved the open question regarding finite-sample coverage guarantees, as it addresses a fundamental theoretical boundary for applying conformal inference to serially dependent time-series data.

### Approved Concepts
- Conformal Seasonal Pools: Represents a new class of training-free, non-parametric conformal forecasting frameworks that serve as a strong performance and calibration benchmark for learned models.

### Approved Open Questions
- Finite-Sample Coverage Guarantees: This is a fundamental theoretical limitation for conformal prediction in time-series, separating practical empirical performance from rigorous safety requirements.

## Links

- [Abstract](https://arxiv.org/abs/2605.03789)
- [PDF](https://arxiv.org/pdf/2605.03789)

