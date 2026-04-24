---
# CSL-compatible fields
title: "SDGF: Fusing Static and Multi-Scale Dynamic Correlations for Multivariate Time Series Forecasting"
author:
  - literal: "Shaoxun Wang"
  - literal: "Xingjun Zhang"
  - literal: "Qianyang Li"
  - literal: "Jiawei Cao"
  - literal: "Zhendong Tan"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.18135"

# Custom fields
paper_id: "2509.18135"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "multivariate-time-series"
  - "wavelet-analysis"
  - "attention-mechanism"
architectures:
  []
datasets:
  []
concept_slugs:
  - "static-dynamic-graph-fusion"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:50:06Z"
created_at: "2026-04-24T05:50:06Z"
---

# SDGF: Fusing Static and Multi-Scale Dynamic Correlations for Multivariate Time Series Forecasting

**Authors**: Shaoxun Wang, Xingjun Zhang, Qianyang Li, Jiawei Cao, Zhendong Tan
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.18135](https://arxiv.org/abs/2509.18135)

## Summary

SDGF addresses the limitations of existing multivariate forecasting models in capturing complex, multi-scale inter-series dependencies. The architecture employs a dual-path approach: a static graph path based on prior knowledge for stable dependencies and a dynamic graph path driven by multi-level wavelet decomposition for multi-scale feature extraction. An attention-gated module integrates these sources, while a multi-kernel dilated convolutional network further refines temporal pattern modeling. Experiments across standard benchmarks show that this fusion strategy significantly improves forecasting accuracy.

## Key Contributions

- Introduces SDGF, a dual-path graph fusion network that captures both long-term stable dependencies via static graphs and evolving associations across temporal scales.
- Proposes an attention-gated fusion module to intelligently integrate static prior knowledge with multi-scale dynamic graph features.
- Demonstrates superior performance over state-of-the-art baselines on multiple real-world multivariate time series forecasting benchmarks.

## Open Questions & Future Work

- [[latent-inter-series-dependency-bottleneck]]

## Key Concepts

- [[static-dynamic-graph-fusion]]: A dual-path graph learning framework that combines static prior-based graphs with multi-scale, adaptively learned dynamic graphs for multivariate time series forecasting.

## Archivist Review

I approved the 'Static-Dynamic Graph Fusion' concept because it defines a generalizable dual-path architectural pattern for balancing static priors and dynamic correlations in multivariate forecasting. I also approved a refined open question regarding the 'Latent Inter-series Dependency Bottleneck', focusing the research challenge on the limitations of current static/dynamic fusion paradigms when faced with non-stationary, latent dependencies. I rejected the initial open question to replace it with a more concise version suited for the vault.

### Approved Concepts
- Static-Dynamic Graph Fusion: The core novelty of the paper is the specific dual-path graph structure learning that merges static prior knowledge with adaptively learned multi-scale dynamic dependencies.

### Approved Open Questions
- Latent Inter-series Dependency Bottleneck: The effectiveness of multivariate forecasting is restricted by the rigidity of current graph structure learning methods, limiting the ability to adapt to complex, evolving, and latent inter-series associations.

### Rejected Candidates
- [open_question] Capturing Complex Evolving Dependencies (`complex-evolving-inter-series-dependencies`) - other: The suggested title and description were reframed into a more specific, technical open-question slug that better highlights the bottleneck nature of the problem.

## Links

- [Abstract](https://arxiv.org/abs/2509.18135)
- [PDF](https://arxiv.org/pdf/2509.18135)

