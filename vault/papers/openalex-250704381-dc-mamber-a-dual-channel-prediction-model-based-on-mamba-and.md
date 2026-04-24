---
# CSL-compatible fields
title: "DC-Mamber: A Dual Channel Prediction Model Based on Mamba and Linear Transformer for Multivariate Time Series Forecasting"
author:
  - literal: "Bing Fan"
  - literal: "Shusen Ma"
  - literal: "Yun‐Bo Zhao"
  - literal: "Gang Xu"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2507.04381"

# Custom fields
paper_id: "2507.04381"
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
processed_at: "2026-04-24T05:50:16Z"
created_at: "2026-04-24T05:50:16Z"
---

# DC-Mamber: A Dual Channel Prediction Model Based on Mamba and Linear Transformer for Multivariate Time Series Forecasting

**Authors**: Bing Fan, Shusen Ma, Yun‐Bo Zhao, Gang Xu
**Date**: 2026-04-21
**Paper ID**: [openalex:2507.04381](https://arxiv.org/abs/2507.04381)

## Summary

DC-Mamber addresses the trade-off between local temporal modeling and global context in multivariate time series forecasting by combining state space models (Mamba) with linear Transformers. The architecture uses a dual-channel approach to simultaneously extract intra-variable patterns and global dependencies, mitigating the quadratic complexity of standard Transformers while overcoming Mamba's limitations in global context sensitivity. A specialized feature-fusion module then synthesizes these distinct representations to produce more accurate predictions. Experimental results demonstrate that this hybrid approach outperforms existing channel-independent and channel-mixing baselines.

## Key Contributions

- Proposes DC-Mamber, a dual-channel architecture that integrates Mamba for local temporal feature extraction and a linear Transformer for global dependency modeling.
- Implements a Dual-Channel Embedding Layer that processes input streams through distinct temporal strategies to capture both intra-variable and inter-variable patterns.
- Achieves state-of-the-art forecasting accuracy across four multivariate time series datasets by balancing linear complexity with global contextual integration.

## Open Questions & Future Work

- [[optimal-feature-fusion-mtsd]]

## Archivist Review

I have approved one open question concerning the optimal fusion of heterogeneous features in dual-channel forecasting architectures, as this remains a broader research challenge beyond this specific paper. The model architecture itself, DC-Mamber, and its specific embedding layer were rejected as they are implementation-specific contributions rather than foundational concepts for the vault.

### Approved Open Questions
- Optimal Feature Fusion Methods: Establishing robust fusion mechanisms is critical for hybrid architectures that attempt to merge disparate feature representations, which is a common challenge in multi-modal or multi-branch neural network designs.

### Rejected Candidates
- [concept] DC-Mamber (`dc-mamber`) - not_novel: The proposed model is a specific architecture implementation that does not represent a sufficiently novel or generalizable architectural paradigm beyond what is already captured by existing hybrid state space-transformer models.
- [concept] Dual-Channel Embedding Layer (`dual-channel-embedding-layer`) - paper_local: This is an implementation detail specific to the DC-Mamber architecture rather than a widely reusable mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2507.04381)
- [PDF](https://arxiv.org/pdf/2507.04381)

