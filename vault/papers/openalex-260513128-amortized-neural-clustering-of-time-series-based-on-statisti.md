---
# CSL-compatible fields
title: "Amortized Neural Clustering of Time Series based on Statistical Features"
author:
  - literal: "Ángel López-Oriona"
  - literal: "Ying Sun"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13128"

# Custom fields
paper_id: "2605.13128"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "amortized-neural-clustering"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:01:13Z"
created_at: "2026-05-16T06:01:13Z"
---

# Amortized Neural Clustering of Time Series based on Statistical Features

**Authors**: Ángel López-Oriona, Ying Sun
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13128](https://arxiv.org/abs/2605.13128)

## Summary

This paper proposes an amortized neural approach to feature-based time series clustering, shifting from standard heuristic algorithms like K-means to a learned, data-driven partitioning framework. By training neural networks on statistical feature spaces, the method effectively recovers complex cluster structures without requiring prior assumptions about the number or geometry of clusters. The framework offers a scalable, automated alternative for clustering temporal data, demonstrating improved empirical accuracy across synthetic and financial time series benchmarks.

## Key Contributions

- Introduces an algorithm-agnostic framework for time series clustering that replaces traditional iterative heuristics with amortized neural inference.
- Demonstrates that learning affinity structures from statistical features (e.g., autocorrelations, quantile autocorrelations) allows for flexible partitioning without prior cluster shape assumptions.
- Implements an automated mechanism to estimate the number of clusters, eliminating the need for ad-hoc model selection.
- Shows superior clustering performance against traditional baselines like K-means and hierarchical clustering, particularly in scenarios where the true number of clusters is unknown.

## Open Questions & Future Work

- [[fuzzy-clustering-extensions-for-time-series]]
- [[hybrid-simulation-self-supervised-clustering]]

## Key Concepts

- [[amortized-neural-clustering]]: A framework for time series clustering that uses amortized neural inference to learn data-driven affinity structures directly from statistical features.

## Archivist Review

The paper introduces a novel amortized approach to clustering that replaces traditional iterative algorithms with a learned neural partitioning rule. I approved the concept and two research directions focused on softening cluster constraints and improving training generalization through hybrid self-supervised paradigms. I maintained a high standard for entry, rejecting generic clustering terms and paper-internal details in favor of broader methodological shifts.

### Approved Concepts
- Amortized Neural Clustering: The approach moves away from traditional iterative heuristics (K-means/medoids) by amortizing the learning of partitioning rules.

### Approved Open Questions
- Fuzzy clustering extensions: This is a fundamental direction for improving the realism of clustering models in complex applications where data does not strictly adhere to single-cluster assignments, such as financial regime-switching.
- Hybridizing simulation and self-supervised training: This addresses the sensitivity of simulation-based methods to model misspecification by providing a more data-driven approach to regularization and generalization.

## Links

- [Abstract](https://arxiv.org/abs/2605.13128)
- [PDF](https://arxiv.org/pdf/2605.13128)

