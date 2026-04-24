---
# CSL-compatible fields
title: "Scalable Memristive-Friendly Reservoir Computing for Time Series Classification"
author:
  - literal: "Coşku Can Horuz"
  - literal: "Andrea Ceni"
  - literal: "Claudio Gallicchio"
  - literal: "Sebastian Otte"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19343"

# Custom fields
paper_id: "2604.19343"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-classification"
  - "reservoir-computing"
  - "neuromorphic-computing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "memristive-friendly-parallelized-reservoirs"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:50:52Z"
created_at: "2026-04-24T05:50:52Z"
---

# Scalable Memristive-Friendly Reservoir Computing for Time Series Classification

**Authors**: Coşku Can Horuz, Andrea Ceni, Claudio Gallicchio, Sebastian Otte
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19343](https://arxiv.org/abs/2604.19343)

## Summary

The paper introduces Memristive-friendly Parallelized Reservoirs (MARS), a novel reservoir computing architecture designed to exploit the physical properties of memristive devices for scalable, energy-efficient sequence modeling. MARS utilizes subtractive skip connections to enable deeper model composition and parallelized computation, achieving significant training speedups and improved predictive performance. The model demonstrates high efficiency in long-sequence classification tasks, outperforming established gradient-based sequence models like Mamba and S5 in both time and accuracy.

## Key Contributions

- Proposed MARS (Memristive-friendly Parallelized Reservoirs), a novel architecture featuring subtractive skip connections for deeper, scalable model composition.
- Achieved up to 21x training speedups over baseline Echo State Networks.
- Demonstrated superior predictive performance on long-sequence benchmarks compared to gradient-based models like LRU, S5, and Mamba, with training times reduced to milliseconds.

## Open Questions & Future Work

- [[automated-hyperparameter-optimization-for-reservoir-computing]]

## Key Concepts

- [[memristive-friendly-parallelized-reservoirs]]: A reservoir computing architecture optimized for memristive hardware that utilizes subtractive skip connections for deeper model composition and parallel processing.

## Archivist Review

I approved the MARS architecture as a significant contribution to scalable, gradient-free reservoir computing that addresses the specific limitations of temporal modeling on neuromorphic hardware. The open question regarding hyperparameter optimization was approved because it addresses a fundamental, recurring bottleneck in fixed-reservoir architectures that prevents broader adoption. Subtractive skip connections were rejected as a subcomponent of the overarching MARS framework.

### Approved Concepts
- Memristive-friendly parallelized reservoirs: It represents a novel structural approach to reservoir computing designed for hardware-native scaling, specifically addressing bottlenecks in depth and parallelization for non-gradient-based models.

### Approved Open Questions
- Automated hyperparameter optimization for reservoir computing: Without systematic optimization, the performance ceiling of reservoir-based neuromorphic systems remains unpredictable across new problem domains.

### Rejected Candidates
- [concept] Subtractive skip connections (`subtractive-skip-connections`) - subcomponent_of_broader_mechanism: This is a specific subcomponent of the proposed MARS architecture rather than a distinct, widely applicable mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.19343)
- [PDF](https://arxiv.org/pdf/2604.19343)

