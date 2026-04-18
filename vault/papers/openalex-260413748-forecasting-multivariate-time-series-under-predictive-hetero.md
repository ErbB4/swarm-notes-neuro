---
# CSL-compatible fields
title: "Forecasting Multivariate Time Series under Predictive Heterogeneity: A Validation-Driven Clustering Framework"
author:
  - literal: "Ziling Ma"
  - literal: "Ángel López Oriona"
  - literal: "Hernando Ombao"
  - literal: "Ying Sun"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13748"

# Custom fields
paper_id: "2604.13748"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "validation-driven-adaptive-pooling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:34:17Z"
created_at: "2026-04-18T05:34:17Z"
---

# Forecasting Multivariate Time Series under Predictive Heterogeneity: A Validation-Driven Clustering Framework

**Authors**: Ziling Ma, Ángel López Oriona, Hernando Ombao, Ying Sun
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13748](https://arxiv.org/abs/2604.13748)

## Summary

This paper addresses the problem of predictive heterogeneity in high-dimensional multivariate time series forecasting by proposing a validation-driven adaptive pooling framework. Unlike methods that group series based on representation similarity, this approach partitions data based on out-of-sample predictive risk estimated through validation error. A leakage-free fallback mechanism ensures that specialization is only employed when it demonstrably outperforms a global model, providing a robust safeguard against negative transfer. The framework supports both point and probabilistic forecasting and maintains efficiency in high-dimensional settings.

## Key Contributions

- Formulates adaptive pooling as a statistical decision problem, prioritizing predictive risk over representation similarity.
- Introduces a leakage-free fallback mechanism that dynamically switches to a global model to prevent performance degradation from poor specialization.
- Demonstrates robust performance on large-scale traffic datasets using Huber and pinball loss functions for point and probabilistic forecasting.

## Open Questions & Future Work

- [[soft-fuzzy-specialization-mts]]

## Key Concepts

- [[validation-driven-adaptive-pooling]]: A framework for adaptive pooling in multivariate time series that uses validation-based predictive risk to determine optimal model specialization.

## Archivist Review

I have approved the core methodological contribution of validation-driven adaptive pooling, as it offers a principled, performance-oriented alternative to traditional feature-based clustering in time series. I also approved the open question regarding soft vs. hard specialization, as it directly addresses a structural limitation of existing clustering approaches in non-stationary or overlapping forecasting regimes. Other candidates were rejected for being generic or lacking sufficient specificity for the vault.

### Approved Concepts
- Validation-driven Adaptive Pooling: It shifts the focus of time series clustering from feature-space similarity to predictive-performance-based partitioning.

### Approved Open Questions
- Soft vs Hard Specialization: Addressing hard assignment restrictions is crucial for improving forecasting robustness in settings where time series do not belong clearly to a single regime, potentially enabling smoother and more accurate predictive performance.

### Rejected Candidates
- [dataset] Traffic datasets (`traffic-datasets`) - generic: Generic reference to a broad category of data rather than a specific, named benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.13748)
- [PDF](https://arxiv.org/pdf/2604.13748)

