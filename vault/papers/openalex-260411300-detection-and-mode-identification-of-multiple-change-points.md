---
# CSL-compatible fields
title: "Detection and Mode-Identification of Multiple Change Points in Tensor Factor Models"
author:
  - literal: "Yuqi Zhang"
  - literal: "Zetai Cen"
  - literal: "Haeran Cho"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11300"

# Custom fields
paper_id: "2604.11300"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "tensor-factor-model-change-point-detection"
  - "mode-identifiability-in-tensor-time-series"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:47:23Z"
created_at: "2026-04-16T05:47:23Z"
---

# Detection and Mode-Identification of Multiple Change Points in Tensor Factor Models

**Authors**: Yuqi Zhang, Zetai Cen, Haeran Cho
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11300](https://arxiv.org/abs/2604.11300)

## Summary

This paper addresses structural change point detection in high-dimensional tensor-valued time series using Tucker decomposition-based factor models. The authors propose a two-stage approach: first, detecting change points by exploiting the underlying low-rank tensor structure, and second, identifying the specific modes associated with each change point. This mode-identification step is shown to improve the estimation accuracy of mode-wise loading spaces following segmentation. The methodology is validated through simulations and applied to New York City taxi usage and Fama-French portfolio returns.

## Key Contributions

- Proposes a change point detection algorithm for tensor-valued time series that leverages Tucker decomposition for computational efficiency.
- Introduces a framework for mode-identification, enabling the pinpointing of specific tensor modes where structural shifts occur.
- Establishes theoretical consistency for both detection and mode-identification under weak moment conditions.
- Demonstrates superior post-segmentation estimation of loading spaces by incorporating mode-identification.

## Key Concepts

- [[tensor-factor-model-change-point-detection]]: A method for detecting structural change points in tensor-valued time series by exploiting low-rank Tucker decomposition structures.
- [[mode-identifiability-in-tensor-time-series]]: A formal framework for identifying specific tensor modes that undergo structural shifts in a factor model.

## Archivist Review

I have approved the core methodological contributions—the tensor-specific change point detection and the mode-identification framework—as these represent significant advancements in analyzing multi-dimensional time series. I rejected the datasets as they are common benchmarks, not unique research contributions. The approved concepts capture the structural inductive biases necessary for tensor time-series analysis.

### Approved Concepts
- Tensor Factor Model Change Point Detection: The framework addresses the non-trivial extension of change point detection from vector time series to high-dimensional tensors, which is a growing area in time-series analysis.
- Mode-Identifiability in Tensor Time Series: Provides a novel approach to interpreting which dimensions of a tensor contribute to structural shifts, enhancing the explainability of tensor models.

### Rejected Candidates
- [dataset] New York City taxi usage (`new-york-city-taxi-usage`) - not_novel: This is a standard real-world benchmark used for demonstration rather than a seminal dataset worth a standalone entry.
- [dataset] Fama--French portfolio returns (`fama-french-portfolio-returns`) - not_novel: This is a well-known, widely available financial dataset rather than a novel research-contributed dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.11300)
- [PDF](https://arxiv.org/pdf/2604.11300)

