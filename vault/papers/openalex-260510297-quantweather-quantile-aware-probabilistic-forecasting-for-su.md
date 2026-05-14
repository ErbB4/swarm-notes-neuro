---
# CSL-compatible fields
title: "QuantWeather: Quantile-Aware Probabilistic Forecasting for Subseasonal Precipitation"
author:
  - literal: "Lei Chen"
  - literal: "Xinyu Su"
  - literal: "Xiaohui Zhong"
  - literal: "Hao Li"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10297"

# Custom fields
paper_id: "2605.10297"
paper_source: "openalex"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "uncertainty-estimation"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dual-head-probabilistic-forecasting-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:40Z"
created_at: "2026-05-14T06:09:40Z"
---

# QuantWeather: Quantile-Aware Probabilistic Forecasting for Subseasonal Precipitation

**Authors**: Lei Chen, Xinyu Su, Xiaohui Zhong, Hao Li
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10297](https://arxiv.org/abs/2605.10297)

## Summary

QuantWeather is a novel end-to-end probabilistic forecasting framework designed for subseasonal precipitation that replaces traditional ensemble post-processing with a dual-head architecture. By jointly optimizing deterministic and probabilistic heads, the model provides reliable uncertainty estimates while allowing for stochastic sampling in a single forward pass. This approach significantly reduces the computational and memory burdens associated with generating and maintaining large reforecast datasets for post-hoc calibration. Evaluations show that the framework achieves higher forecasting skill than standard ensemble methods across key performance metrics.

## Key Contributions

- QuantWeather, a dual-head probabilistic forecasting framework, achieves superior uncertainty calibration compared to standard ensemble-based methods for subseasonal precipitation.
- The model supports efficient stochastic sampling, enabling high-fidelity probabilistic outputs with a single forward pass, significantly reducing computational and storage overhead.
- Experimental results demonstrate that QuantWeather outperforms conventional ensemble methods in probabilistic skill while eliminating the need for expensive post-hoc reforecast calibration.

## Open Questions & Future Work

- [[quantile-calibration-ensemble-dispersion-tradeoff]]

## Key Concepts

- [[dual-head-probabilistic-forecasting-framework]]: A forecasting architecture that jointly optimizes separate heads for deterministic and probabilistic outputs to enable efficient end-to-end uncertainty quantification.

## Archivist Review

I have approved a generalized concept for the dual-head architecture used in the paper, as it represents a broader, reusable mechanism for uncertainty-aware forecasting. I have also approved a refined open question regarding the fundamental trade-offs between probabilistic calibration and ensemble dispersion in multi-objective architectures. Other candidates were rejected as near-duplicates or application-specific variants.

### Approved Concepts
- Dual-Head Probabilistic Forecasting Framework: This architecture provides a scalable alternative to computationally expensive post-hoc ensemble calibration by embedding probabilistic estimation directly into the model training objective.

### Approved Open Questions
- Quantile Calibration Dispersion Trade-off: Understanding this trade-off is essential for developing models that simultaneously deliver high-accuracy point forecasts and robust, well-calibrated uncertainty estimates without compromising the benefits of ensemble averaging.

### Rejected Candidates
- [concept] QuantWeather Framework (`quantweather-framework`) - duplicate_existing: This is a specific application instance of a dual-head framework, which is better captured by the generalized concept slug.
- [open_question] Balancing Quantile Calibration and Dispersion (`balance-quantile-calibration-ensemble-dispersion`) - other: The title was rewritten for clarity and conciseness.

## Links

- [Abstract](https://arxiv.org/abs/2605.10297)
- [PDF](https://arxiv.org/pdf/2605.10297)

