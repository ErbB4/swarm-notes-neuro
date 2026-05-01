---
# CSL-compatible fields
title: "EvoTSC: Evolving Feature Learning Models for Time Series Classification via Genetic Programming"
author:
  - literal: "Xuanhao Yang"
  - literal: "Bing Xue"
  - literal: "Mengjie Zhang"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25499"

# Custom fields
paper_id: "2604.25499"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "classification"
  - "genetic-programming"
  - "feature-learning"
  - "model-generalization"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T06:04:21Z"
created_at: "2026-05-01T06:04:21Z"
---

# EvoTSC: Evolving Feature Learning Models for Time Series Classification via Genetic Programming

**Authors**: Xuanhao Yang, Bing Xue, Mengjie Zhang
**Date**: 2026-04-28
**Paper ID**: [openalex:2604.25499](https://arxiv.org/abs/2604.25499)

## Summary

EvoTSC is a genetic programming-based framework designed to evolve lightweight, highly generalizable feature learning models for time series classification. By incorporating prior expert knowledge within a multi-layer program structure, the approach effectively identifies relevant time series features while maintaining computational efficiency. The framework utilizes a Pareto tournament selection mechanism to ensure consistent performance across diverse data subsets, addressing challenges associated with label scarcity. Experimental results on univariate datasets indicate that EvoTSC achieves superior classification performance compared to established benchmarks.

## Key Contributions

- Introduces EvoTSC, a genetic programming framework that automates the construction of lightweight feature learning models for time series classification.
- Proposes a multi-layer program structure that integrates domain-specific expert knowledge to guide the evolutionary search.
- Implements a tailored Pareto tournament selection strategy to enhance generalization and mitigate overfitting in scenarios with limited labeled data.

## Open Questions & Future Work

- [[gp-multivariate-tsc-bottleneck]]
- [[gp-subtree-transfer-learning-bottleneck]]

## Archivist Review

I approved two open questions concerning the scaling of Genetic Programming to multivariate domains and the transferability of evolved features. I rejected all candidate concepts because the proposed methods (e.g., Pareto tournament selection) are generic optimization strategies or application-specific implementation details that do not yet warrant permanent status in the vault.

### Approved Open Questions
- GP Multivariate TSC Bottleneck: Multivariate time series are standard in real-world industrial and clinical applications; overcoming the univariate bottleneck is essential for the practical utility of evolutionary feature learning.
- GP Subtree Transfer Learning Bottleneck: Addressing the computational cost and cold-start problem of GP models through transfer learning is a key step toward making them competitive with pre-trained foundation models.

### Rejected Candidates
- [open_question] Extending GP for Multivariate TSC (`gp-multivariate-tsc`) - duplicate_existing: Replaced by a more formally titled and context-aware version to match vault standards.
- [open_question] Transfer Learning for GP Subtrees (`gp-subtree-transfer-learning`) - duplicate_existing: Replaced by a more formally titled and context-aware version to match vault standards.

## Links

- [Abstract](https://arxiv.org/abs/2604.25499)
- [PDF](https://arxiv.org/pdf/2604.25499)

