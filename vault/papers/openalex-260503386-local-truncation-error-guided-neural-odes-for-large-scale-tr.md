---
# CSL-compatible fields
title: "Local Truncation Error-Guided Neural ODEs for Large Scale Traffic Forecasting"
author:
  - literal: "Xiao Zhang"
  - literal: "Yafei Li"
  - literal: "Ruixiang Wang"
  - literal: "Wei Wei"
  - literal: "Shuo He"
  - literal: "Mingliang Xu"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03386"

# Custom fields
paper_id: "2605.03386"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "neural-odes"
  - "spatiotemporal-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "local-truncation-error-guided-neural-odes"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:44:04Z"
created_at: "2026-05-08T05:44:04Z"
---

# Local Truncation Error-Guided Neural ODEs for Large Scale Traffic Forecasting

**Authors**: Xiao Zhang, Yafei Li, Ruixiang Wang, Wei Wei, Shuo He, Mingliang Xu
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03386](https://arxiv.org/abs/2605.03386)

## Summary

LTE-ODE addresses the over-smoothing limitations of Neural ODEs in spatiotemporal traffic forecasting by treating Local Truncation Error (LTE) as an unsupervised inductive bias. Instead of rigid manifold regularization, the model uses LTE to map a spatial attention mask, enabling seamless switching between continuous ODE evolution in stable states and discrete compensation branches at shock points. This approach eliminates gradient conflicts while maintaining high-precision performance across diverse large-scale traffic datasets.

## Key Contributions

- Introduces LTE-ODE, an architecture that dynamically balances continuous evolution and discrete shock compensation using Local Truncation Error.
- Identifies that standard manifold regularization in Neural ODEs causes gradient conflicts and attention collapse in traffic forecasting.
- Achieves state-of-the-art performance on large-scale traffic benchmarks with improved robustness to non-linear fluctuations compared to baseline models.

## Open Questions & Future Work

- [[neural-ode-continuity-shock-dilemma]]

## Key Concepts

- [[local-truncation-error-guided-neural-odes]]: A Neural ODE architecture that uses Local Truncation Error to dynamically modulate between continuous evolution and discrete shock compensation.

## Archivist Review

I approved the proposed Neural ODE architecture as a novel approach to the continuity-shock problem and the corresponding open question that formalizes the limitation of manifold regularization in continuous-time models. These contributions are significant for physics-informed machine learning and provide a clear, reusable pathway for future research in spatiotemporal forecasting. No other candidates were provided or identified.

### Approved Concepts
- Local Truncation Error-Guided Neural ODEs: The core novelty is using LTE as a guidance signal to adaptively handle shock points in Neural ODEs without explicit manifold regularization.

### Approved Open Questions
- Reconciling Continuity and Shocks: This is a fundamental limitation in physics-informed machine learning, as most existing frameworks struggle to distinguish between informative anomalies and numerical noise, creating a bottleneck for high-precision, non-linear spatiotemporal forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2605.03386)
- [PDF](https://arxiv.org/pdf/2605.03386)

