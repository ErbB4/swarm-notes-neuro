---
# CSL-compatible fields
title: "Physical Fidelity Reconstruction via Improved Consistency-Distilled Flow Matching for Dynamical Systems"
author:
  - literal: "Sicheng Ma"
  - literal: "Tianyue Yang"
  - literal: "Xiuzhe Wu"
  - literal: "Xiao Xue"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05975"

# Custom fields
paper_id: "2605.05975"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-augmented-generation"
  - "latent-distribution-matching-ldm"
architectures:
  []
datasets:
  []
concept_slugs:
  - "consistency-distilled-flow-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:09:08Z"
created_at: "2026-05-10T06:09:08Z"
---

# Physical Fidelity Reconstruction via Improved Consistency-Distilled Flow Matching for Dynamical Systems

**Authors**: Sicheng Ma, Tianyue Yang, Xiuzhe Wu, Xiao Xue
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05975](https://arxiv.org/abs/2605.05975)

## Summary

This paper addresses the computational latency of high-fidelity flow reconstruction in scientific machine learning by proposing a consistency-distilled flow-matching approach. By distilling an optimal-transport teacher into a one-step student model, the authors achieve significant speedups and memory efficiency while maintaining high reconstruction fidelity. The method allows for conditional inference by initializing trajectories from low-fidelity observations, demonstrating robustness on fluid benchmarks including Smoke Buoyancy, Turbulent Channel Flow, and Kolmogorov Flow.

## Key Contributions

- Introduces a consistency distillation framework that converts optimal-transport flow-matching models into efficient one-step generators for high-fidelity flow reconstruction.
- Demonstrates a 12x inference speedup and superior SSIM performance (23.1% improvement) compared to directly-trained one-step consistency models on complex fluid dynamics benchmarks.
- Enables conditional reconstruction from low-fidelity observations by initializing generative trajectories from noised inputs, without requiring retraining of the teacher model.

## Open Questions & Future Work

- [[adaptive-inference-noise-schedules-for-physical-distillation]]

## Key Concepts

- [[consistency-distilled-flow-matching]]: A distillation framework that compresses optimal-transport flow-matching teacher models into one-step consistency models for efficient scientific flow reconstruction.

## Archivist Review

I approved the consistency-distilled flow-matching concept as it provides a generalizable distillation paradigm for low-latency scientific reconstruction. The open question regarding adaptive inference noise schedules was also approved as it addresses a fundamental limitation in the robustness of current one-step generative approaches in physical settings. Fluid benchmarks mentioned were rejected as they represent domain-specific test cases rather than standardized foundation datasets.

### Approved Concepts
- Consistency-Distilled Flow Matching: This represents the primary methodology for enabling high-fidelity, one-step reconstruction for dynamical systems, which is the core contribution of the paper.

### Approved Open Questions
- Adaptive Inference Noise Schedules: The current reliance on manually tuned, fixed inference parameters limits the robustness of one-step reconstruction models across diverse scientific datasets. Improving the adaptive scheduling of inference-time noise injection is technically critical to maintaining physical fidelity without compromising the speed advantages of consistency models.

### Rejected Candidates
- [dataset] Smoke Buoyancy (`smoke-buoyancy`) - low_impact: This is a specific fluid benchmark, not a widely used, critical dataset deserving a permanent vault note.
- [dataset] Turbulent Channel Flow (`turbulent-channel-flow`) - low_impact: This is a specific fluid benchmark, not a widely used, critical dataset deserving a permanent vault note.
- [dataset] Kolmogorov Flow (`kolmogorov-flow`) - low_impact: This is a specific fluid benchmark, not a widely used, critical dataset deserving a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2605.05975)
- [PDF](https://arxiv.org/pdf/2605.05975)

