---
created_at: '2026-05-03T06:02:36Z'
source_papers:
- '[[openalex-260427967-differentiable-latent-structure-discovery-for-interpretable]]'
title: Non-Gaussian Likelihoods for GPs
---

**Background:** Process convolution Gaussian processes define the covariance structure of multi-task models through kernel convolutions, which inherently rely on Gaussian noise assumptions. Integrating these models with non-Gaussian likelihoods is necessary to accommodate diverse distributions and discrete states common in clinical time series data.

**Question / Future Work:** Extend the process convolution framework to incorporate non-Gaussian likelihoods (e.g., Poisson, Bernoulli, categorical) to better model clinical events like intubation, medication administration, or discrete mortality states.

**Why It Matters:** This is a fundamental bottleneck for deploying continuous-time Gaussian process models in real-world clinical or physical systems that are not inherently Gaussian.

**Evidence:** more flexible likelihood formulations would be necessary to capture the heterogeneity of clinical time series and to jointly model discrete patient states