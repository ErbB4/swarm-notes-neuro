---
# CSL-compatible fields
title: "Martingale-Consistent Self-Supervised Learning"
author:
  - literal: "Moritz Gögl"
  - literal: "Hanwen Xing"
  - literal: "Christopher Yau"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11846"

# Custom fields
paper_id: "2605.11846"
paper_source: "openalex"
domain: "nlp"
tags:
  - "self-supervised-learning"
  - "representation-learning"
  - "uncertainty-estimation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "martingale-consistent-ssl"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:58Z"
created_at: "2026-05-15T06:15:58Z"
---

# Martingale-Consistent Self-Supervised Learning

**Authors**: Moritz Gögl, Hanwen Xing, Christopher Yau
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11846](https://arxiv.org/abs/2605.11846)

## Summary

This paper introduces a self-supervised learning (SSL) framework designed to ensure prediction coherence when information levels change, such as under partial observations. By leveraging martingale theory, the method constrains the expectation of refined predictions to match coarse-view predictions, effectively preventing systematic drift that standard invariance objectives overlook. The framework is supported by a novel unbiased two-sample Monte Carlo estimator and is shown to enhance representation stability, robustness, and calibration across various data modalities.

## Key Contributions

- Introduced a martingale-consistent SSL framework that enforces prediction coherence between coarse and refined views.
- Proposed a two-sample Monte Carlo estimator using stochastic refinement to enable practical training without systematic prediction drift.
- Demonstrated improved robustness and calibration under partial-observation regimes across time-series, tabular, and image benchmarks.

## Open Questions & Future Work

- [[martingale-consistency-scalability-and-refinement]]

## Key Concepts

- [[martingale-consistent-ssl]]: A self-supervised learning framework that enforces martingale-based coherence between coarse and refined model views to prevent systematic prediction drift.

## Archivist Review

The review focused on the novelty and theoretical grounding of the Martingale-Consistent SSL objective as a method for ensuring stability under changing information levels, which is highly relevant to time-series forecasting under partial observability. The approved open question addresses the practical bottlenecks inherent in this specific training regime, namely refinement efficiency and scaling behavior, while the approved concept offers a distinct approach to SSL coherence that complements existing representation learning frameworks.

### Approved Concepts
- Martingale-Consistent Self-Supervised Learning: It introduces a theoretically grounded objective for SSL using martingale theory to prevent systematic prediction drift across varying information levels.

### Approved Open Questions
- Scalability and Refinement in Martingale SSL: The effectiveness of the martingale-consistent objective relies heavily on the quality and efficiency of the refinement mechanism, which currently poses a challenge for scaling to large foundation models.

## Links

- [Abstract](https://arxiv.org/abs/2605.11846)
- [PDF](https://arxiv.org/pdf/2605.11846)

