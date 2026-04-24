---
# CSL-compatible fields
title: "DPAnet: Dual Pyramid Attention Network for Multivariate Time Series Forecasting"
author:
  - literal: "Qianyang Li"
  - literal: "Xingjun Zhang"
  - literal: "Shaoxun Wang"
  - literal: "Jia Wei"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.14868"

# Custom fields
paper_id: "2509.14868"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "attention-mechanisms"
  - "multi-scale-modeling"
  - "spectral-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dpanet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:49:42Z"
created_at: "2026-04-24T05:49:42Z"
---

# DPAnet: Dual Pyramid Attention Network for Multivariate Time Series Forecasting

**Authors**: Qianyang Li, Xingjun Zhang, Shaoxun Wang, Jia Wei
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.14868](https://arxiv.org/abs/2509.14868)

## Summary

DPANet addresses the challenge of capturing complex multi-scale and multi-frequency dependencies in long-term time series forecasting. The model employs a dual-pyramid architecture: one branch utilizes progressive downsampling for temporal dynamics, while the other applies band-pass filtering for spectral resolutions. A cross-pyramid fusion mechanism facilitates interactive information exchange at hierarchical levels, allowing global context to guide local representation learning and yielding state-of-the-art results.

## Key Contributions

- Proposed DPANet, a novel architecture that decouples and concurrently models temporal multi-scale dynamics and spectral multi-resolution periodicities using parallel pyramids.
- Introduced the Cross-Pyramid Fusion Block for deep hierarchical information exchange between temporal and spectral representations.
- Achieved state-of-the-art performance on long-term time series forecasting benchmarks compared to existing Transformer and MLP-based baselines.

## Open Questions & Future Work

- [[optimal-multiresolution-fusion-strategy]]

## Key Concepts

- [[dpanet]]: A dual-stream architecture for time series forecasting that independently models temporal multi-scale dynamics and spectral multi-resolution periodicities before fusing them.

## Archivist Review

I approved the Dual Pyramid Attention Network as a distinct architectural paradigm for multi-scale time series modeling and an open question regarding the optimality of hierarchical fusion strategies. I rejected the Cross-Pyramid Fusion Block as it is a submodule of the main architecture. No datasets were approved as none were specifically named or unique to this paper's contribution.

### Approved Concepts
- Dual Pyramid Attention Network: It provides a architectural paradigm for decomposing and modeling multi-scale temporal dynamics and spectral periodicities in parallel.

### Approved Open Questions
- Optimal Multiresolution Fusion Strategy: Moving beyond fixed hierarchical fusion is critical for robust handling of non-stationary time series where the coupling between temporal and frequency features may change dynamically.

### Rejected Candidates
- [concept] Cross-Pyramid Fusion Block (`cross-pyramid-fusion-block`) - subcomponent_of_broader_mechanism: This is a sub-component of the overarching Dual Pyramid Attention Network architecture.

## Links

- [Abstract](https://arxiv.org/abs/2509.14868)
- [PDF](https://arxiv.org/pdf/2509.14868)

