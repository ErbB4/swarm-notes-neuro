---
# CSL-compatible fields
title: "GCov-based portmanteau test"
author:
  - literal: "Joann Jasiak"
  - literal: "Aryan Manafi Neyazi"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2312.05373"

# Custom fields
paper_id: "2312.05373"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "generalized-covariance-test"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:45:33Z"
created_at: "2026-04-17T05:45:33Z"
---

# GCov-based portmanteau test

**Authors**: Joann Jasiak, Aryan Manafi Neyazi
**Date**: 2026-04-14
**Paper ID**: [openalex:2312.05373](https://arxiv.org/abs/2312.05373)

## Summary

This paper introduces a new portmanteau test for detecting nonlinear serial dependence (NLSD) in time series, specifically designed for non-Gaussian errors and dynamic model residuals. The method extends the Generalized Covariance (GCov) framework to an infinite set of nonlinear autocovariance conditions and provides an asymptotic χ² distribution for hypothesis testing. The authors also propose a bootstrap version of the test to enhance finite-sample performance, demonstrating its efficacy on time series with explosive behavior like commodity prices and cryptocurrencies. The approach is validated through a simulation study on mixed causal-noncausal autoregressive models and an empirical application to aluminum price data.

## Key Contributions

- Introduces a novel portmanteau-type test for nonlinear serial dependence (NLSD) using Generalized Covariance (GCov) residuals.
- Derives asymptotic χ² distribution results for the GCov test under local alternatives and extends the framework to an infinite set of nonlinear autocovariance conditions.
- Proposes a GCov bootstrap test to improve size accuracy in finite samples and for diagnostic purposes in maximum-likelihood estimated models.

## Open Questions & Future Work

- [[one-step-residual-diagnostics-bottleneck]]
- [[optimal-nonlinear-generator-selection]]

## Key Concepts

- [[generalized-covariance-test]]: A semi-parametric specification test that uses nonlinear autocovariances to detect serial dependence in residuals of dynamic models.

## Archivist Review

The paper introduces a robust framework for testing nonlinear dependence in time series. I have approved the Generalized Covariance Test as a key concept, given its utility as a diagnostic tool for non-Gaussian dynamic models. I have also refined and approved two open questions that highlight the practical challenges of diagnostic automation and the theoretical difficulty of optimal generator selection. No datasets were approved as none provided a significant, novel contribution to the field.

### Approved Concepts
- Generalized Covariance Test: It provides a unified, semi-parametric framework for nonlinear serial dependence testing in dynamic models, which is a common challenge in non-Gaussian time series.

### Approved Open Questions
- One-Step Residual Diagnostics Bottleneck: Current diagnostic workflows are often prone to omission due to complexity; a reliable, single-step diagnostic tool could significantly improve model validation practices in applied time series analysis.
- Optimal Nonlinear Generator Selection: The efficiency and sensitivity of GCov-based tests are highly dependent on the choice of generator functions, making this a critical optimization problem for reliable inference.

### Rejected Candidates
- [open_question] Convenient One-Step Residual Diagnostics (`convenient-one-step-residual-diagnostics`) - duplicate_existing: Renamed to a more descriptive slug and title for clarity and to avoid overlap.
- [open_question] Optimal Nonlinear Transformation Selection (`optimal-nonlinear-transformation-selection`) - duplicate_existing: Renamed to 'Optimal Nonlinear Generator Selection' for conciseness and technical accuracy.

## Links

- [Abstract](https://arxiv.org/abs/2312.05373)
- [PDF](https://arxiv.org/pdf/2312.05373)

