---
# CSL-compatible fields
title: "MambaRain: Multi-Scale Mamba-Attention Framework for 0-3 Hour Precipitation Nowcasting"
author:
  - literal: "Chunlei Shi"
  - literal: "Cui Wu"
  - literal: "Xiang Xu"
  - literal: "Hao Li"
  - literal: "Ni Fan"
  - literal: "Xue Han"
  - literal: "Yongchao Feng, Yufeng Zhu, Boyu Liu, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14606"

# Custom fields
paper_id: "2605.14606"
paper_source: "openalex"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "mamba-attention-hybrid-spatiotemporal-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:09:07Z"
created_at: "2026-05-17T06:09:07Z"
---

# MambaRain: Multi-Scale Mamba-Attention Framework for 0-3 Hour Precipitation Nowcasting

**Authors**: Chunlei Shi, Cui Wu, Xiang Xu, Hao Li, Ni Fan, Xue Han, Yongchao Feng, Yufeng Zhu, Boyu Liu, Zengliang Zang, Hongbin Wang, Yanlan Yang, Dan Niu
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14606](https://arxiv.org/abs/2605.14606)

## Summary

MambaRain is a hybrid encoder-decoder framework designed to overcome performance degradation in precipitation nowcasting beyond 90 minutes. By integrating Mamba’s linear-complexity state space mechanisms for global temporal modeling with self-attention for explicit spatial dependency capture, the model effectively addresses the limitations of purely sequential or attention-based architectures. A custom spectral loss formulation further improves forecast sharpness, resulting in superior performance over current deterministic models in the 2-3 hour horizon.

## Key Contributions

- Introduces MambaRain, a hybrid architecture combining selective state space models (Mamba) for temporal dynamics and self-attention for spatial correlation modeling.
- Enables effective 0-3 hour precipitation nowcasting, extending reliable prediction horizons beyond the traditional 2-hour window.
- Proposes a spectral loss formulation to minimize blurring artifacts in chaotic precipitation fields, preserving fine-scale motion information.

## Open Questions & Future Work

- [[probabilistic-precipitation-nowcasting-uncertainty-bottleneck]]

## Key Concepts

- [[mamba-attention-hybrid-spatiotemporal-modeling]]: An architectural pattern that integrates selective state-space models for global temporal dynamics with self-attention for local spatial feature extraction in spatiotemporal tasks.

## Archivist Review

I approved the hybrid architecture pattern rather than the specific model name to ensure reusability. I also approved the uncertainty bottleneck in nowcasting as it is a fundamental challenge for the transition from deterministic to operational-grade weather AI. The spectral loss was rejected as it is a common signal processing technique applied in a paper-local manner.

### Approved Concepts
- Mamba-Attention Hybrid Spatiotemporal Modeling: Provides a concrete structural blueprint for combining the temporal efficiency of selective state-space models with the spatial fidelity of self-attention.

### Approved Open Questions
- Probabilistic Nowcasting Uncertainty Bottleneck: Deterministic point estimates in chaotic systems often miss the multi-modal nature of extreme weather, making uncertainty quantification a vital next step for operational adoption.

### Rejected Candidates
- [concept] MambaRain (`mambarain`) - paper_local: Specific architecture names are typically paper-local; the underlying hybrid approach is more broadly reusable.

## Links

- [Abstract](https://arxiv.org/abs/2605.14606)
- [PDF](https://arxiv.org/pdf/2605.14606)

