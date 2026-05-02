---
# CSL-compatible fields
title: "Beyond Fixed Formulas: Data-Driven Linear Predictor for Efficient Diffusion Models"
author:
  - literal: "Zhirong Shen"
  - literal: "Rui Huang"
  - literal: "Jiacheng Liu"
  - literal: "Chang Zou"
  - literal: "Peiliang Cai"
  - literal: "Shikang Zheng"
  - literal: "Zhengyi Shi"
  - literal: "Liang Feng"
  - literal: "Linfeng Zhang"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26365"

# Custom fields
paper_id: "2604.26365"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "diffusion-models"
  - "inference-acceleration"
  - "transformers"
  - "caching"
  - "efficient-sampling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "learnable-linear-predictor"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:50:03Z"
created_at: "2026-05-02T05:50:03Z"
---

# Beyond Fixed Formulas: Data-Driven Linear Predictor for Efficient Diffusion Models

**Authors**: Zhirong Shen, Rui Huang, Jiacheng Liu, Chang Zou, Peiliang Cai, Shikang Zheng, Zhengyi Shi, Liang Feng, Linfeng Zhang
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26365](https://arxiv.org/abs/2604.26365)

## Summary

This paper addresses the inference latency bottleneck in Diffusion Transformers by replacing traditional hand-crafted feature caching formulas with a data-driven approach called Learnable Linear Predictor (L2P). L2P learns per-timestep weights to reconstruct current features from historical trajectories, enabling significantly more aggressive skipping strategies than static methods. Experiments across FLUX.1-dev and Qwen-Image models demonstrate substantial latency improvements and FLOPs reduction without sacrificing visual quality. The framework is highly efficient, requiring only approximately 20 seconds of training on a single GPU.

## Key Contributions

- Introduced L2P (Learnable Linear Predictor), a training-free acceleration framework for Diffusion Transformers (DiTs) using per-timestep learnable weights.
- Demonstrated 4.55x FLOPs reduction and 4.15x latency speedup on FLUX.1-dev while maintaining superior visual fidelity compared to fixed-formula caching methods.
- Showcased robustness of learned predictors at aggressive acceleration factors (up to 7.18x) on Qwen-Image models where baseline methods suffer from quality degradation.

## Open Questions & Future Work

- [[adaptive-diffusion-acceleration-transferability]]

## Key Concepts

- [[learnable-linear-predictor]]: A data-driven feature caching framework for diffusion models that replaces fixed forecasting formulas with learnable per-timestep weights.

## Archivist Review

I approved the Learnable Linear Predictor concept as a reusable, architecture-agnostic mechanism for accelerating diffusion model inference. I also approved a refined open question regarding the transferability of adaptive acceleration strategies, as current data-driven approaches require specific calibration that limits their universal deployment. I maintained strict selectivity by rejecting redundant or overly narrow descriptors.

### Approved Concepts
- Learnable Linear Predictor (L2P): It provides a systematic, data-driven alternative to rigid, heuristic-based feature caching in diffusion models, enabling more aggressive skip-sampling without quality degradation.

### Approved Open Questions
- Adaptive Diffusion Acceleration Transferability: Solving this would enable fully 'plug-and-play' acceleration, eliminating the overhead of task-specific training or calibration for efficient inference.

## Links

- [Abstract](https://arxiv.org/abs/2604.26365)
- [PDF](https://arxiv.org/pdf/2604.26365)

