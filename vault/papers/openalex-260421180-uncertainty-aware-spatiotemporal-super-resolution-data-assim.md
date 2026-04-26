---
# CSL-compatible fields
title: "Uncertainty-Aware Spatiotemporal Super-Resolution Data Assimilation with Diffusion Models"
author:
  - literal: "Aditya Sai Pranith Ayapilla"
  - literal: "Kazuya Miyashita"
  - literal: "Yuki Yasuda"
  - literal: "Ryo Onishi"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21180"

# Custom fields
paper_id: "2604.21180"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-augmented-generation"
  - "uncertainty-weighted-mean-squared-error"
architectures:
  []
datasets:
  []
concept_slugs:
  - "diffsrda"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:35Z"
created_at: "2026-04-26T05:52:35Z"
---

# Uncertainty-Aware Spatiotemporal Super-Resolution Data Assimilation with Diffusion Models

**Authors**: Aditya Sai Pranith Ayapilla, Kazuya Miyashita, Yuki Yasuda, Ryo Onishi
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21180](https://arxiv.org/abs/2604.21180)

## Summary

DiffSRDA is a novel probabilistic framework for spatiotemporal data assimilation that leverages denoising diffusion models to perform super-resolution on chaotic fluid flows. By conditioning on low-resolution forecast time series and sparse high-resolution observations, the model produces ensembles of high-resolution analyses that quantify uncertainty in dynamically active regions. The method offers a computationally efficient alternative to traditional high-resolution ensemble methods like EnKF, while supporting robust, training-free adaptation to changing sensor configurations through observation-consistency guidance.

## Key Contributions

- Proposed DiffSRDA, a diffusion-based data assimilation framework that enables high-resolution analysis of chaotic systems using only low-cost low-resolution forecasts.
- Demonstrated that DiffSRDA achieves reconstruction quality comparable to Ensemble Kalman Filter (EnKF) while providing physically meaningful uncertainty estimates.
- Established that few-step reverse diffusion is sufficient for accurate cycling and showed that score-based guidance allows for training-free adaptation to sensor-layout shifts.

## Open Questions & Future Work

- [[generalizing-likelihood-guidance-for-complex-observations]]
- [[balancing-guidance-efficiency-and-flexibility]]

## Key Concepts

- [[diffsrda]]: A diffusion-based data assimilation framework that integrates low-resolution model forecasts with sparse high-resolution observations to produce probabilistic high-resolution analyses.

## Archivist Review

I have approved the core framework DiffSRDA, as it represents a significant methodological shift by replacing expensive high-resolution ensembles with diffusion-based sampling. I also approved two high-level open questions that address the current fundamental limitations of diffusion-based DA: the transition from idealized on-grid observations to complex real-world sensor arrays and the computational efficiency bottleneck imposed by inference-time guidance.

### Approved Concepts
- DiffSRDA: It represents a novel fusion of denoising diffusion models with data assimilation for super-resolution, providing an alternative to traditional ensemble Kalman filters.

### Approved Open Questions
- Guidance for Complex Observations: It is a critical bottleneck for deploying diffusion-based data assimilation in real-world geophysical and climate settings where sensors are irregularly spaced or indirect.
- Efficiency-Flexible Guidance Balance: Achieving this balance is vital for making diffusion-based data assimilation computationally competitive with traditional ensemble methods in real-time, high-dimensional cycling applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.21180)
- [PDF](https://arxiv.org/pdf/2604.21180)

