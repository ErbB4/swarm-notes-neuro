---
# CSL-compatible fields
title: "Sequential Inference for Gaussian Processes: A Signal Processing Perspective"
author:
  - literal: "Daniel Waxman"
  - literal: "Fernando Llorente"
  - literal: "Petar M. Djurić"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28163"

# Custom fields
paper_id: "2604.28163"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "bayesian-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:03:07Z"
created_at: "2026-05-03T06:03:07Z"
---

# Sequential Inference for Gaussian Processes: A Signal Processing Perspective

**Authors**: Daniel Waxman, Fernando Llorente, Petar M. Djurić
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.28163](https://arxiv.org/abs/2604.28163)

## Summary

This paper provides a systematic, tutorial-style overview of Gaussian Processes (GPs) specifically for sequential, incremental, and streaming inference tasks. By reframing GP methodologies through a signal processing lens, the authors bridge the gap between classical statistical signal processing and modern machine learning paradigms. The work serves as a foundational guide for researchers and practitioners, offering a coherent roadmap for implementing sequential GP models in applications like state-space modeling, adaptive sensing, and time series forecasting.

## Key Contributions

- Provides a comprehensive tutorial-style overview of Gaussian Processes (GPs) focused on sequential, incremental, and streaming inference.
- Bridges methodological gaps between classical signal processing and modern machine learning frameworks for temporal data.
- Organizes recent advancements in sequential GP inference into a unified roadmap for practical deployment in real-world systems.

## Open Questions & Future Work

- [[gp-nonstationary-high-dim]]
- [[decentralized-gp-scalability]]

## Archivist Review

The paper is a high-level tutorial review of Gaussian Processes for sequential inference. As it is a survey rather than a novel method proposal, no new concepts are introduced. However, the identified open questions regarding non-stationarity in high dimensions and decentralized scalability are substantial, foundational bottlenecks for the field of sequential probabilistic modeling, and thus warrant inclusion in the vault.

### Approved Open Questions
- Scalable nonstationary sequential GPs: This is a fundamental bottleneck for deploying GP-based sequential estimation in real-world applications where the underlying signal dynamics are inherently nonstationary and high-dimensional. Bridging this gap is essential to make GPs competitive with modern neural architectures.
- Scalability in decentralized GPs: As distributed sensing and multi-agent systems become more ubiquitous, the ability to perform robust, collaborative probabilistic inference in large-scale networks will be critical for intelligent and adaptive system control.

## Links

- [Abstract](https://arxiv.org/abs/2604.28163)
- [PDF](https://arxiv.org/pdf/2604.28163)

