---
# CSL-compatible fields
title: "A High Dimensional Wild Bootstrap Max-Test for Detecting the Presence of Significant Predictors"
author:
  - literal: "Jonathan B. Hill"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27813"

# Custom fields
paper_id: "2604.27813"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:03:34Z"
created_at: "2026-05-03T06:03:34Z"
---

# A High Dimensional Wild Bootstrap Max-Test for Detecting the Presence of Significant Predictors

**Authors**: Jonathan B. Hill
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27813](https://arxiv.org/abs/2604.27813)

## Summary

This paper introduces a block bootstrap max-test designed for detecting significant predictors in high-dimensional settings where the number of covariates p grows exponentially relative to sample size n. By employing a max-statistic over marginal regression parameters under a physical dependence framework, the method bypasses the need for complex covariance estimation and Bonferroni corrections. The approach provides robust size control and effective signal detection for weakly dependent, non-stationary time series data, as demonstrated through empirical analysis of the VIX volatility index.

## Key Contributions

- Proposes a block bootstrap max-test for high-dimensional correlation screening where the number of covariates p grows exponentially with n.
- Eliminates the need for explicit covariance matrix estimation and post-estimation Bonferroni corrections by using a max-statistic approach over marginal regression parameters.
- Demonstrates robust size control and performance against sparse signals under weak dependence and non-stationarity, validated via VIX index empirical application.

## Open Questions & Future Work

- [[adaptive-covariate-index-weak-dependence]]
- [[weakening-moment-conditions-hd-screening]]

## Archivist Review

The paper proposes a high-dimensional bootstrap max-test for predictor screening. Since the method is primarily a statistical inference framework rather than a novel representation or forecasting architecture, no specific 'concept' stood out as a generally reusable temporal method worthy of a permanent vault entry. The open questions, however, highlight substantial theoretical bottlenecks in high-dimensional dependence analysis and were approved for tracking.

### Approved Open Questions
- Adaptive Covariate Selection Under Dependence: Developing such an index would bridge the gap between simple marginal screening and complex post-model-selection inference, potentially enhancing the detection of informative predictors in dependent data.
- Weakening Moment Conditions for Screening: Weakening these moment requirements is technically important to ensure the theory covers a wider array of financial and economic models where extreme observations are common.

## Links

- [Abstract](https://arxiv.org/abs/2604.27813)
- [PDF](https://arxiv.org/pdf/2604.27813)

