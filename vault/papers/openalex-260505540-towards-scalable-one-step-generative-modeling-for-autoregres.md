---
# CSL-compatible fields
title: "Towards Scalable One-Step Generative Modeling for Autoregressive Dynamical System Forecasting"
author:
  - literal: "Tianyue Yang"
  - literal: "Xiao Xue"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05540"

# Custom fields
paper_id: "2605.05540"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "generative-modeling"
  - "spatio-temporal-forecasting"
  - "physical-dynamics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "melisa-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:26Z"
created_at: "2026-05-10T06:04:26Z"
---

# Towards Scalable One-Step Generative Modeling for Autoregressive Dynamical System Forecasting

**Authors**: Tianyue Yang, Xiao Xue
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05540](https://arxiv.org/abs/2605.05540)

## Summary

MeLISA is a latent-free autoregressive generative surrogate designed for high-dimensional physical dynamics that avoids the computational overhead of iterative denoising or auxiliary latent compression. By leveraging a blockwise stochastic transition kernel optimized with Window-Consistency MeanFlow and Time Increment Consistency losses, the model maintains physical statistical structures over long-horizon rollouts. Evaluated on 2D Kolmogorov and turbulent channel flows, MeLISA achieves superior performance in both short-term accuracy and long-term statistical metrics (e.g., kinetic energy spectra) compared to neural operators, while retaining inference efficiency.

## Key Contributions

- Introduces MeLISA, a latent-free autoregressive generative surrogate using pixel-space MeanFlow to enable single-evaluation blockwise forecasting.
- Develops Window-Consistency MeanFlow and Time Increment Consistency objectives to preserve turbulent flow statistics and prevent long-horizon drift.
- Outperforms neural-operator baselines on Kolmogorov and channel-flow benchmarks in both short-term accuracy and long-term energy spectra preservation while maintaining faster inference speeds.

## Open Questions & Future Work

- [[scaling-one-step-generative-models-to-3d-physical-dynamics]]

## Key Concepts

- [[melisa-framework]]: A latent-free autoregressive generative surrogate that uses MeanFlow and consistency-based objectives to achieve efficient, physically accurate long-horizon trajectory forecasting.

## Archivist Review

I approved the MeLISA framework because it provides a distinct, latent-free approach to high-dimensional autoregressive generative forecasting, addressing the efficiency-vs-accuracy trade-off in physical surrogates. The open question regarding 3D scaling was approved as it represents a significant, well-defined barrier to the deployment of one-step generation techniques in complex physical systems. No datasets were approved as the benchmarks used were standard flow dynamics cases rather than novel, reusable datasets.

### Approved Concepts
- MeanFlow Long-term Invariant Spatiotemporal Consistency Autoregressive Models (MeLISA): Introduces a novel latent-free autoregressive generative framework that enables single-pass high-resolution temporal forecasting while maintaining long-term physical consistency.

### Approved Open Questions
- Scaling one-step generative models: Scalability to 3D systems is the primary bottleneck for widespread adoption of generative surrogates in real-world fluid dynamics and engineering applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.05540)
- [PDF](https://arxiv.org/pdf/2605.05540)

