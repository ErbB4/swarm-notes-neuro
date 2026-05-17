---
# CSL-compatible fields
title: "ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing"
author:
  - literal: "Yixuan Jia"
  - literal: "Siyi Chen"
  - literal: "Yida Pan"
  - literal: "Xiao Li"
  - literal: "Lianghe Shi"
  - literal: "Chanyong Jung"
  - literal: "Haijie Yuan"
  - literal: "Ismail Alkhouri, Yue Wu"
  - literal: "Saiprasad Ravishankar"
  - literal: "Jeffrey A. Fessler"
  - literal: "Qing Qu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14285"

# Custom fields
paper_id: "2605.14285"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "diffusion-forcing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:09:00Z"
created_at: "2026-05-17T06:09:00Z"
---

# ForcingDAS: Unified and Robust Data Assimilation via Diffusion Forcing

**Authors**: Yixuan Jia, Siyi Chen, Yida Pan, Xiao Li, Lianghe Shi, Chanyong Jung, Haijie Yuan, Ismail Alkhouri, Yue Wu, Saiprasad Ravishankar, Jeffrey A. Fessler, Qing Qu
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14285](https://arxiv.org/abs/2605.14285)

## Summary

ForcingDAS is a robust data assimilation framework that addresses error accumulation in dynamical systems by learning a joint-trajectory prior rather than iterative frame-to-frame transitions. By leveraging Diffusion Forcing with frame-specific noise levels, the method effectively captures long-horizon temporal dependencies in non-Markovian scenarios. Crucially, it provides a unified interface for filtering and smoothing, allowing users to select tasks at inference time without retraining. Evaluation across multiple scientific benchmarks demonstrates that a single model can outperform regime-specific learned and classical baselines.

## Key Contributions

- Introduces ForcingDAS, a unified data assimilation framework that replaces frame-to-frame transition models with joint-trajectory priors via Diffusion Forcing.
- Enables a single trained model to perform both filtering (nowcasting) and smoothing (reanalysis) tasks by adjusting the inference schedule without retraining.
- Achieves superior robustness against error accumulation in non-Markovian observational settings, outperforming specialized baselines on 2D Navier-Stokes and global atmospheric state estimation benchmarks.

## Open Questions & Future Work

- [[causal-only-smoothing-bottleneck]]
- [[physics-constrained-assimilation-integration]]

## Key Concepts

- [[diffusion-forcing]]: A training technique that assigns independent noise levels to individual frames, allowing models to learn joint-trajectory priors instead of traditional frame-to-frame transitions.

## Archivist Review

The paper introduces a significant shift in data assimilation by moving from frame-to-frame transitions to trajectory-based diffusion priors. 'Diffusion Forcing' is approved as a foundational concept. The two open questions address critical bottlenecks in existing assimilation paradigms—specifically architectural limitations in backward information flow and the need for physical consistency in data-driven models—which are central challenges in time-series and scientific machine learning.

### Approved Concepts
- Diffusion Forcing: Central mechanism enabling the framework to learn joint-trajectory priors and avoid error accumulation in dynamical systems.

### Approved Open Questions
- Causal-only Smoothing Bottleneck: This is a fundamental architectural limitation that restricts the efficacy of information propagation from future observations to past states, which is critical for high-performance smoothing and reanalysis.
- Physics-constrained Assimilation Integration: Integrating physics constraints is crucial for ensuring the physical realism and reliability of assimilated state estimates in scientific and climate applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.14285)
- [PDF](https://arxiv.org/pdf/2605.14285)

