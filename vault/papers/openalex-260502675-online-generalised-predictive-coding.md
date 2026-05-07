---
# CSL-compatible fields
title: "Online Generalised Predictive Coding"
author:
  - literal: "Mehran H. Z. Bazargani"
  - literal: "Szymon Urbas"
  - literal: "Adeel Razi"
  - literal: "Thomas Brendan Murphy"
  - literal: "Karl Friston"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02675"

# Custom fields
paper_id: "2605.02675"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "bayesian-inference"
  - "online-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "online-dynamic-expectation-maximisation-odem"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:05:01Z"
created_at: "2026-05-07T06:05:01Z"
---

# Online Generalised Predictive Coding

**Authors**: Mehran H. Z. Bazargani, Szymon Urbas, Adeel Razi, Thomas Brendan Murphy, Karl Friston
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02675](https://arxiv.org/abs/2605.02675)

## Summary

This paper presents Online Dynamic Expectation Maximisation (ODEM), a framework for online data assimilation that jointly estimates latent states, model parameters, and uncertainty. By employing a separation of temporal scales, the method allows for fast Bayesian belief updating of hidden states while performing slower, iterative updates for parameters and precision. Numerical experiments with chaotic, non-linear systems confirm the method's ability to track latent dynamics effectively, even when the generative model is misspecified. This approach provides a computationally efficient, neuro-mimetic solution for inference and learning in volatile, real-time environments.

## Key Contributions

- Introduces Online Dynamic Expectation Maximisation (ODEM), which extends the standard DEM framework for real-time online data assimilation.
- Implements a temporal scale separation strategy that decouples fast Bayesian state inference from the slower updating of model parameters and precisions.
- Demonstrates the robustness of ODEM in tracking latent states for non-linear and chaotic generative processes, even under model mismatch scenarios.

## Open Questions & Future Work

- [[non-stationary-kernels-in-gpc]]

## Key Concepts

- [[online-dynamic-expectation-maximisation-odem]]: A framework for online data assimilation that uses temporal scale separation to jointly infer latent states, model parameters, and uncertainty.

## Archivist Review

I have approved the Online Dynamic Expectation Maximisation (ODEM) framework as a novel, reusable approach to real-time joint inference and the corresponding open question on non-stationary kernels. The candidate regarding learnable smoothness matrices was rejected as it represents a specific technical parameterization choice rather than a fundamental research bottleneck.

### Approved Concepts
- Online Dynamic Expectation Maximisation (ODEM): Introduces a novel online adaptation of the Dynamic Expectation Maximisation (DEM) framework for triple estimation (states, parameters, uncertainty) in dynamic environments.

### Approved Open Questions
- Non-stationary Kernels in GPC: Non-stationary kernels would significantly increase the flexibility of predictive coding models for real-world scenarios where system dynamics are non-homogeneous over time, a critical requirement for robust online inference.

### Rejected Candidates
- [open_question] Learnable Smoothness Matrices (`learnable-smoothness-matrices`) - subcomponent_of_broader_mechanism: This is a specific implementation detail regarding model parameterization rather than a foundational, high-level open research problem.

## Links

- [Abstract](https://arxiv.org/abs/2605.02675)
- [PDF](https://arxiv.org/pdf/2605.02675)

