---
created_at: '2026-05-16T06:01:30Z'
source_papers:
- '[[openalex-260513150-generative-modeling-of-approximately-periodic-time-series-by]]'
title: Scalable Inference for Modulated GP Covariance
---

**Background:** Gaussian Process models for time series with periodic structure face a trade-off between capturing intra-repetition dynamics and allowing for inter-repetition variability.

**Question / Future Work:** Future research is required to adapt scalable or approximate inference techniques (such as those using inducing variables) to the proposed covariance modulation framework, as evaluating the likelihood with the Schur product of kernel matrices currently becomes computationally prohibitive as the number of repetitions increases.

**Why It Matters:** The current method's computational complexity limits its application to datasets with a large number of repetitions; addressing this is critical for the model's scalability in industrial contexts.

**Evidence:** Scaling the likelihood optimization to large numbers of repetitions will require sparse or approximate inference techniques [13, 5], which could be adapted to the proposed covariance modulation framework.