---
# CSL-compatible fields
title: "S2TX: Cross-Attention Multi-Scale State-Space Transformer for Time Series Forecasting"
author:
  - literal: "Zihao Wu"
  - literal: "Juncheng Dong"
  - literal: "Haoming Yang"
  - literal: "Vahid Tarokh"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2502.11340"

# Custom fields
paper_id: "2502.11340"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "attention"
  - "multi-scale"
architectures:
  - "Transformer"
  - "Mamba"
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:49:49Z"
created_at: "2026-04-24T05:49:49Z"
---

# S2TX: Cross-Attention Multi-Scale State-Space Transformer for Time Series Forecasting

**Authors**: Zihao Wu, Juncheng Dong, Haoming Yang, Vahid Tarokh
**Date**: 2026-04-21
**Paper ID**: [openalex:2502.11340](https://arxiv.org/abs/2502.11340)

## Summary

S2TX is a novel time series forecasting architecture that addresses the isolation of variate processing and multiscale representation learning. By combining the long-range modeling capabilities of Mamba with local window-based Transformer attention, the framework captures comprehensive temporal dependencies. An integrated cross-attention mechanism facilitates synergistic communication between global and local features, resulting in improved accuracy and efficient memory usage across diverse benchmarks.

## Key Contributions

- Proposes S2TX, a hybrid architecture integrating Mamba for long-range cross-variate context and Transformers for local window attention.
- Employs cross-attention mechanisms to enable variate-level interactions and bridge global-local feature representations.
- Achieves state-of-the-art forecasting performance across six standard benchmarks while maintaining low computational memory overhead.

## Open Questions & Future Work

- [[local-cross-variate-correlation-modeling]]
- [[multi-scale-intermediate-learning]]

## Archivist Review

I approved two open questions that address significant architectural bottlenecks in multivariate time series forecasting, specifically regarding local-variate correlation and multi-scale temporal modeling. I rejected the S2TX architecture itself as it is a specific hybrid of existing state-space models and Transformers, rather than a sufficiently novel, reusable concept for the vault.

### Approved Open Questions
- Modeling Local Cross-Variate Correlations: This represents a significant architectural bottleneck in multivariate time series forecasting that prevents models from capturing the complex, localized interaction patterns between different variables.
- Learning Intermediate Time Scales: Capturing intermediate scales is essential for extremely long sequences where significant temporal variations occur between the extremes of global and local contexts.

### Rejected Candidates
- [concept] S2TX Architecture (`s2tx-architecture`) - not_novel: The architecture is a specific implementation of existing building blocks (Mamba/Transformer) rather than a novel, generally reusable primitive.

## Links

- [Abstract](https://arxiv.org/abs/2502.11340)
- [PDF](https://arxiv.org/pdf/2502.11340)

