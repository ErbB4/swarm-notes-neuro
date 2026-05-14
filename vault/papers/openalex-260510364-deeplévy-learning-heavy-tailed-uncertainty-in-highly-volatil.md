---
# CSL-compatible fields
title: "DeepLévy: Learning Heavy-Tailed Uncertainty in Highly Volatile Time Series"
author:
  - literal: "Yang Yang"
  - literal: "Du Yin"
  - literal: "Hao Xue"
  - literal: "Flora D. Salim"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10364"

# Custom fields
paper_id: "2605.10364"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "deeplevy"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:08:57Z"
created_at: "2026-05-14T06:08:57Z"
---

# DeepLévy: Learning Heavy-Tailed Uncertainty in Highly Volatile Time Series

**Authors**: Yang Yang, Du Yin, Hao Xue, Flora D. Salim
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10364](https://arxiv.org/abs/2605.10364)

## Summary

DeepLévy is a novel probabilistic forecasting framework designed to handle heavy-tailed uncertainty in highly volatile time series. By moving away from likelihood-based inference, it instead learns mixtures of Lévy stable distributions through the minimization of discrepancy between empirical and parametric characteristic functions. This approach allows the model to flexibly capture extreme events and non-Gaussian behaviors over multiple forecasting horizons. Experiments confirm that DeepLévy consistently outperforms existing state-of-the-art models in tail risk assessment.

## Key Contributions

- Introduces DeepLévy, a neural framework for heavy-tailed uncertainty estimation in time series using mixtures of Lévy stable distributions.
- Replaces intractable likelihood-based inference with characteristic function matching to enable stable learning of non-Gaussian distributions.
- Demonstrates superior tail risk metric performance over state-of-the-art probabilistic models under high volatility.

## Open Questions & Future Work

- [[multivariate-stable-distributions-temporal-tail-dynamics]]

## Key Concepts

- [[deeplevy]]: A neural framework for probabilistic forecasting that models heavy-tailed uncertainty by learning mixtures of Lévy stable distributions via characteristic functions.

## Archivist Review

I approved DeepLévy as it offers a distinct, theoretically grounded approach to heavy-tailed uncertainty estimation by moving from density-based to characteristic-function-based optimization. The identified open question is approved because it addresses a clear technical bottleneck in moving from univariate to multivariate risk modeling for heavy-tailed phenomena. No other candidates were proposed.

### Approved Concepts
- DeepLévy: It introduces a novel framework for modeling heavy-tailed uncertainty in volatile time series by bypassing intractable likelihoods using characteristic function matching.

### Approved Open Questions
- Multivariate Stable Distributions and Temporal Tail Dynamics: Multivariate modeling is essential for capturing inter-asset correlations during market shocks, and temporal tail dynamics would allow for more accurate dynamic risk assessment in non-stationary series.

## Links

- [Abstract](https://arxiv.org/abs/2605.10364)
- [PDF](https://arxiv.org/pdf/2605.10364)

