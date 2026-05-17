---
# CSL-compatible fields
title: "Adaptive Long-Run Variance Thresholding for Sparse Covariance Estimation in High-Dimensional Time Series"
author:
  - literal: "Wenhao Zhang"
  - literal: "Zhaoxing Gao"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14491"

# Custom fields
paper_id: "2605.14491"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-long-run-variance-thresholding"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:07:20Z"
created_at: "2026-05-17T06:07:20Z"
---

# Adaptive Long-Run Variance Thresholding for Sparse Covariance Estimation in High-Dimensional Time Series

**Authors**: Wenhao Zhang, Zhaoxing Gao
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14491](https://arxiv.org/abs/2605.14491)

## Summary

This paper addresses the challenge of sparse covariance estimation in high-dimensional time series, where temporal dependencies invalidate standard thresholding methods designed for i.i.d. data. The authors propose an adaptive thresholding procedure that integrates long-run variance estimates directly into the thresholding process. The method is shown to achieve optimal convergence rates and support recovery consistency under weak dependence conditions. Empirical evaluations confirm that this approach significantly outperforms existing thresholding methods in both simulation and real-world datasets like gene expression and stock returns.

## Key Contributions

- Introduces a novel entry-specific thresholding method that explicitly incorporates long-run variance to handle temporal autocorrelation in high-dimensional data.
- Proves consistency under the spectral norm and establishes optimal convergence rates for the proposed sparse covariance estimator.
- Demonstrates theoretically and empirically that conventional thresholding methods intended for independent data fail to achieve support recovery consistency in the presence of temporal dependence.

## Open Questions & Future Work

- [[theoretical-justification-for-bandwidth-selection-in-hac-covariance-estimation]]

## Key Concepts

- [[adaptive-long-run-variance-thresholding]]: A thresholding procedure for sparse covariance estimation that adjusts entry-wise thresholds using long-run variance to account for temporal dependencies.

## Archivist Review

I approved the core concept of adaptive long-run variance thresholding as it provides a distinct, statistically-grounded approach to covariance estimation under temporal dependence. The open question regarding bandwidth selection is a common, substantial bottleneck in high-dimensional estimation that merits ongoing tracking. Other candidates were rejected to prioritize the primary methodological contribution.

### Approved Concepts
- Adaptive Long-Run Variance Thresholding: It enables accurate sparse covariance estimation in high-dimensional settings by explicitly accounting for the impact of temporal autocorrelation on sample covariance estimators.

### Approved Open Questions
- Theoretical justification for bandwidth selection: The selection of regularization and bandwidth parameters is critical for the robustness of high-dimensional sparse estimators, yet this remains a common heuristic gap in statistical literature.

## Links

- [Abstract](https://arxiv.org/abs/2605.14491)
- [PDF](https://arxiv.org/pdf/2605.14491)

