---
# CSL-compatible fields
title: "Covariance Filters and Neural Networks Over Hilbert Spaces"
author:
  - literal: "Claudio Battiloro"
  - literal: "Andrea Cavallo"
  - literal: "Elvin Isufi"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.13178"

# Custom fields
paper_id: "2509.13178"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "functional-data-analysis"
  - "neural-networks"
  - "statistical-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "hilbert-covariance-networks"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:52:33Z"
created_at: "2026-04-24T05:52:33Z"
---

# Covariance Filters and Neural Networks Over Hilbert Spaces

**Authors**: Claudio Battiloro, Andrea Cavallo, Elvin Isufi
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.13178](https://arxiv.org/abs/2509.13178)

## Summary

This paper extends the paradigm of Covariance Neural Networks (VNNs) to infinite-dimensional Hilbert spaces, addressing the theoretical limitations of finite-dimensional graph signal processing. The authors introduce Hilbert coVariance Filters (HVFs) and build Hilbert coVariance Networks (HVNs), which leverage empirical covariance operators for feature extraction. The framework is theoretically grounded in its relationship to Functional PCA and provides a versatile approach for processing complex signals, including multivariate functions and those in Reproducing Kernel Hilbert Spaces (RKHS). Experimental results confirm that the proposed HVNs achieve robust performance on time-series classification tasks.

## Key Contributions

- Introduces Hilbert coVariance Filters (HVFs) and Hilbert coVariance Networks (HVNs) to generalize covariance-based convolution to infinite-dimensional Hilbert spaces.
- Proves that empirical HVFs are capable of recovering the Functional Principal Component Analysis (FPCA) of the filtered signals, bridging functional statistics and deep learning.
- Demonstrates superior classification performance on time-series benchmarks compared to standard MLPs and traditional FPCA-based methods.

## Open Questions & Future Work

- [[hvn-convergence-transferability-bottleneck]]

## Key Concepts

- [[hilbert-covariance-networks]]: A convolutional learning framework for infinite-dimensional Hilbert space signals utilizing empirical covariance operators as filtering mechanisms.

## Archivist Review

The approved concept, Hilbert coVariance Networks (HVNs), represents a significant generalization of existing covariance-based learning to functional data, offering a robust, theoretically grounded architecture likely to influence future time-series and functional analysis research. The open question regarding convergence and transferability addresses a fundamental gap in linking empirical, discrete neural operators with their infinite-dimensional theoretical counterparts. No datasets were approved as they were not uniquely central to the paper's contribution.

### Approved Concepts
- Hilbert coVariance Networks (HVNs): HVNs generalize graph-based covariance learning from finite-dimensional signals to infinite-dimensional Hilbert spaces, providing a new class of operators for functional data analysis.

### Approved Open Questions
- HVN Convergence and Transferability Bottleneck: Establishing convergence and transferability is fundamental for justifying the use of empirical, finite-dimensional neural network architectures as reliable approximations of theoretical models defined in infinite-dimensional Hilbert spaces.

## Links

- [Abstract](https://arxiv.org/abs/2509.13178)
- [PDF](https://arxiv.org/pdf/2509.13178)

