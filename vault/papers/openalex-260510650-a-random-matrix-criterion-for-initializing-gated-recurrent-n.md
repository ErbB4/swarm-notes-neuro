---
# CSL-compatible fields
title: "A Random-Matrix Criterion for Initializing Gated Recurrent Neural Networks"
author:
  - literal: "Tommaso Fioratti"
  - literal: "Riccardo Marcaccioli"
  - literal: "Francesco Casola"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10650"

# Custom fields
paper_id: "2605.10650"
paper_source: "openalex"
domain: "time-series"
tags:
  - "reservoir-computing"
  - "initialization"
  - "recurrent-neural-networks"
  - "dynamical-systems"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "critical-reservoir-initialization-criterion"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:53Z"
created_at: "2026-05-14T06:10:53Z"
---

# A Random-Matrix Criterion for Initializing Gated Recurrent Neural Networks

**Authors**: Tommaso Fioratti, Riccardo Marcaccioli, Francesco Casola
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10650](https://arxiv.org/abs/2605.10650)

## Summary

This paper proposes a random-matrix-based criterion to determine optimal weight initialization for gated recurrent neural networks, particularly within reservoir computing frameworks. By identifying the critical phase transition point between ordered and chaotic dynamics, the authors define a gain parameter that optimizes memory and representational richness. Empirical validation shows that this criterion accurately predicts the optimal configuration for gated-RNN reservoirs on chaotic forecasting tasks. The results provide a theoretical foundation for more robust weight initialization strategies.

## Key Contributions

- Derivation of a simple random-matrix-based criterion to estimate the critical gain g_c for gated recurrent neural networks.
- Demonstration that the proposed criterion accurately predicts the optimal gain for peak reservoir performance on chaotic time-series forecasting tasks.
- Provision of a theoretical design principle for initialization schemes that balance ordered and chaotic dynamics.

## Open Questions & Future Work

- [[expressivity-of-zero-bias-gated-rnns]]
- [[eoc-analysis-for-biased-networks]]

## Key Concepts

- [[critical-reservoir-initialization-criterion]]: A random-matrix-based criterion for identifying the critical gain parameter that separates ordered from chaotic regimes in recurrent neural network initialization.

## Archivist Review

The paper provides a formal theoretical bridge between random matrix theory and the initialization of gated RNNs. I approved the proposed initialization criterion as a reusable design principle and the two open questions concerning the role of bias in expressivity and EOC analysis, as these represent fundamental theoretical bottlenecks in recurrent network dynamics.

### Approved Concepts
- Critical Reservoir Initialization Criterion: Provides a principled, theoretically-grounded method for weight initialization in recurrent structures, bridging the gap between random matrix theory and empirical reservoir performance.

### Approved Open Questions
- Expressivity of zero-bias gated RNNs: Determining the impact of symmetry constraints on expressivity is fundamental to understanding the design limits of reservoir computing architectures.
- EOC analysis for biased networks: Extending the EOC analysis to biased networks is critical for creating initialization schemes that are robust to realistic weight and bias distributions.

## Links

- [Abstract](https://arxiv.org/abs/2605.10650)
- [PDF](https://arxiv.org/pdf/2605.10650)

