---
# CSL-compatible fields
title: "One-Step Graph-Structured Neural Flows for Irregular Multivariate Time Series Classification"
author:
  - literal: "Mengzhou Gao"
  - literal: "Kaiwei Wang"
  - literal: "Pengfei Jiao"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10179"

# Custom fields
paper_id: "2605.10179"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "graph-structured-neural-flows"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:16Z"
created_at: "2026-05-14T06:09:16Z"
---

# One-Step Graph-Structured Neural Flows for Irregular Multivariate Time Series Classification

**Authors**: Mengzhou Gao, Kaiwei Wang, Pengfei Jiao
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10179](https://arxiv.org/abs/2605.10179)

## Summary

Neural Flows often struggle with capturing inter-variable dependencies due to their one-step integration nature. The proposed Graph-Structured Neural Flows (GSNF) address this by integrating graph structures into the flow dynamics and applying auxiliary self-supervision via trajectory divergence and forward-backward consistency. This enables efficient and expressive modeling of irregular multivariate time series for classification tasks. Extensive experiments demonstrate that GSNF provides superior accuracy with reduced computational overhead compared to traditional ODE-based neural models.

## Key Contributions

- Introduces GSNF, a framework that models inter-variable interactions in one-step neural flows using graph structures.
- Proposes two self-supervision strategies—interaction-aware trajectory re-initialization and reverse-time consistency—to regularize graph learning and trajectory generation.
- GSNF achieves state-of-the-art classification performance on five benchmark datasets while maintaining competitive computational efficiency compared to standard numerical ODE solvers.

## Open Questions & Future Work

- [[time-varying-interaction-graph-learning]]

## Key Concepts

- [[graph-structured-neural-flows]]: A neural flow framework that incorporates graph-structured constraints and auxiliary self-supervision to model complex inter-variable dependencies in irregular time series.

## Archivist Review

I have approved the core GSNF framework as a novel synthesis of graph-based inductive biases and neural flows for irregular time series. The open question regarding time-varying graph learning was also approved as it addresses a fundamental limitation in current continuous-time modeling. Other candidates were deemed redundant or local to this specific implementation.

### Approved Concepts
- Graph-Structured Neural Flows (GSNF): It is the core architectural contribution of the paper, addressing the challenge of modeling inter-variable interactions in neural flow architectures.

### Approved Open Questions
- Learning Time-Varying Interaction Graphs: This is a critical limitation because real-world physical and clinical systems often exhibit dependencies that shift in response to events or temporal state changes, rendering static graph assumptions insufficiently expressive.

## Links

- [Abstract](https://arxiv.org/abs/2605.10179)
- [PDF](https://arxiv.org/pdf/2605.10179)

