---
# CSL-compatible fields
title: "Adaptive Runge-Kutta Dynamics for Spatiotemporal Prediction"
author:
  - literal: "Xuanle Zhao"
  - literal: "Yue Sun"
  - literal: "Ziyi Wang"
  - literal: "Bo Xu"
  - literal: "Tielin Zhang"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2405.14504"

# Custom fields
paper_id: "2405.14504"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "spatiotemporal-prediction"
  - "physics-informed-learning"
  - "pde-modeling"
  - "video-prediction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-runge-kutta-dynamics"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:00Z"
created_at: "2026-04-24T05:51:00Z"
---

# Adaptive Runge-Kutta Dynamics for Spatiotemporal Prediction

**Authors**: Xuanle Zhao, Yue Sun, Ziyi Wang, Bo Xu, Tielin Zhang
**Date**: 2026-04-21
**Paper ID**: [openalex:2405.14504](https://arxiv.org/abs/2405.14504)

## Summary

This paper addresses the limitations of existing physics-informed neural networks in capturing complex spatiotemporal dynamics by introducing an adaptive second-order Runge-Kutta integration scheme. By embedding this adaptive solver directly into the architecture, the model improves the precision of state-transition estimations for PDEs. Additionally, a frequency-enhanced Fourier module is utilized to capture complex dynamic patterns, resulting in superior performance on spatiotemporal and video prediction tasks with higher computational efficiency.

## Key Contributions

- Introduces a physical-guided neural network architecture that integrates an adaptive second-order Runge-Kutta solver to accurately track spatiotemporal state evolution.
- Proposes a frequency-enhanced Fourier module to improve the estimation of spatiotemporal dynamics, capturing complex dependencies better than standard convolutional or recurrent alternatives.
- Achieves state-of-the-art performance on spatiotemporal and video prediction benchmarks while significantly reducing total parameter count.

## Open Questions & Future Work

- [[generalizing-pde-learning-for-unknown-dynamics]]

## Key Concepts

- [[adaptive-runge-kutta-dynamics]]: A neural network integration method that employs an adaptive second-order Runge-Kutta solver to explicitly model physical state transitions in spatiotemporal dynamics.

## Archivist Review

I approved the adaptive Runge-Kutta concept as a distinct methodological contribution for differentiable physics and the open question regarding PDE learning generalization as a foundational research bottleneck. The frequency-enhanced module was rejected as it represents a common architectural pattern rather than a novel contribution. No datasets were approved as none were specifically named or defined as the central reusable benchmark for the field.

### Approved Concepts
- Adaptive Runge-Kutta Dynamics: It shifts the paradigm from fixed-step neural integration to adaptive solving, providing a more robust architectural primitive for physics-informed spatiotemporal modeling.

### Approved Open Questions
- Generalizing PDE Learning Methods: Addressing this bottleneck is essential for the move from task-specific PINNs to general-purpose foundation models for physical dynamics.

### Rejected Candidates
- [concept] Frequency-enhanced Fourier Module (`frequency-enhanced-fourier-module`) - not_novel: Fourier-based modules are already well-established; this specific variant is a minor architectural variation rather than a fundamental innovation.

## Links

- [Abstract](https://arxiv.org/abs/2405.14504)
- [PDF](https://arxiv.org/pdf/2405.14504)

