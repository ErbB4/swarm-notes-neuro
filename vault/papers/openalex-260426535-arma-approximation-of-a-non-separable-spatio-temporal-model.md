---
# CSL-compatible fields
title: "ARMA approximation of a Non-separable Spatio-Temporal Model with Fractional Smoothnesses in Space and Time"
author:
  - literal: "S. Knutsen Furset"
  - literal: "Geir‐Arne Fuglstad"
  - literal: "Espen R. Jakobsen"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26535"

# Custom fields
paper_id: "2604.26535"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "spatio-temporal-modeling"
  - "stochastic-partial-differential-equations"
  - "matérn-covariance"
  - "varma"
architectures:
  []
datasets:
  []
concept_slugs:
  - "rational-approximation-for-spde-discretization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:50:16Z"
created_at: "2026-05-02T05:50:16Z"
---

# ARMA approximation of a Non-separable Spatio-Temporal Model with Fractional Smoothnesses in Space and Time

**Authors**: S. Knutsen Furset, Geir‐Arne Fuglstad, Espen R. Jakobsen
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26535](https://arxiv.org/abs/2604.26535)

## Summary

This paper addresses computational limitations in spatio-temporal modeling using diffusion-based extensions of the Matérn covariance model. By applying rational approximations to the governing space-time fractional stochastic partial differential equation, the authors derive a Vector Autoregressive Moving Average (VARMA) process representation that accommodates arbitrary smoothness in both dimensions. The proposed method is theoretically supported by pointwise convergence proofs and validated through empirical simulations and an application to French daily temperature data.

## Key Contributions

- Proposes a discretization method using rational approximations in time to convert space-time fractional SPDE models into VARMA processes, enabling flexible fractional smoothness modeling.
- Establishes theoretical convergence results and explicit pointwise error rates for the covariance function approximation with respect to spatial-temporal resolution.
- Demonstrates through simulation and a study of daily mean temperatures in France that accurate temporal smoothness specification significantly improves forecasting performance.

## Open Questions & Future Work

- [[spatial-resolution-sensitivity-spatio-temporal-inference]]

## Key Concepts

- [[rational-approximation-for-spde-discretization]]: A discretization technique that leverages rational approximations to represent space-time fractional stochastic partial differential equations as computationally tractable VARMA processes.

## Archivist Review

The review focused on identifying the core computational innovation, which is the rational approximation of SPDEs to facilitate flexible temporal smoothness, and the distinct unresolved challenge regarding spatial resolution sensitivity. Routine items such as VARMA processes and daily temperature data were rejected as either standard or non-reusable.

### Approved Concepts
- Rational Approximation for SPDE Discretization: Provides a robust, reusable computational pathway for implementing fractional smoothness in time for SPDE-based spatio-temporal models, which was previously restrictive.

### Approved Open Questions
- Spatial resolution sensitivity analysis: Understanding the relationship between spatial discretization density and predictive stability is critical for the reliable deployment of these models in automated or high-stakes environmental forecasting tasks.

## Links

- [Abstract](https://arxiv.org/abs/2604.26535)
- [PDF](https://arxiv.org/pdf/2604.26535)

