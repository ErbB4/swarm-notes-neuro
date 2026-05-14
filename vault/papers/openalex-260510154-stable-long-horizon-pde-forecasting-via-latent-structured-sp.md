---
# CSL-compatible fields
title: "Stable Long-Horizon PDE Forecasting via Latent Structured Spectral Propagators"
author:
  - literal: "Xiaoxiao Lu"
  - literal: "Ye Yuan"
  - literal: "Jiahao Shi"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10154"

# Custom fields
paper_id: "2605.10154"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "structured-spectral-propagator"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:00Z"
created_at: "2026-05-14T06:10:00Z"
---

# Stable Long-Horizon PDE Forecasting via Latent Structured Spectral Propagators

**Authors**: Xiaoxiao Lu, Ye Yuan, Jiahao Shi
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10154](https://arxiv.org/abs/2605.10154)

## Summary

This paper addresses error accumulation and dynamic drift in autoregressive PDE forecasting by proposing the Structured Spectral Propagator (SSP). The framework utilizes an analysis-propagation-synthesis design that maps inputs to a time-consistent latent space, isolates recurrent dynamics from spatial details, and evolves spectral modes using a frequency-conditioned linear backbone. This explicit architectural bias significantly improves stability and reduces relative L2 errors for long-horizon temporal extrapolation.

## Key Contributions

- Proposes a Structured Spectral Propagator (SSP) that decouples latent dynamics from spatial reconstruction to mitigate error accumulation in PDE forecasting.
- Introduces an analysis-propagation-synthesis framework that uses a frequency-conditioned linear backbone and nonlinear spectral closure to maintain stability.
- Demonstrates up to 48.9% reduction in relative L2 error compared to existing state-of-the-art neural operator surrogates on long-horizon PDE benchmarks.

## Open Questions & Future Work

- [[long-horizon-pde-stability-extrapolation]]

## Key Concepts

- [[structured-spectral-propagator]]: A neural forecasting framework that models PDE dynamics by evolving spectral modes within a propagation-oriented latent space.

## Archivist Review

The Structured Spectral Propagator was approved as it represents a robust architectural paradigm for PDE surrogates by separating latent state representation from spectral evolution. The open question regarding long-horizon stability in PDE forecasting addresses a fundamental bottleneck in the field of neural operators. No datasets were approved as none were specifically named or highlighted as a unique benchmarking contribution.

### Approved Concepts
- Structured Spectral Propagator: It is the core architectural innovation that enables stable, long-horizon PDE forecasting by decoupling latent dynamics from reconstruction.

### Approved Open Questions
- Stability in Long-Horizon Forecasting: Long-horizon forecasting is essential for scientific utility, and the current reliance on finite-time supervision makes generalization to long-time dynamics a significant bottleneck in deploying neural surrogates for real-world physical systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.10154)
- [PDF](https://arxiv.org/pdf/2605.10154)

