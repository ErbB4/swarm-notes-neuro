---
created_at: '2026-05-07T06:05:01Z'
source_papers:
- '[[openalex-260502675-online-generalised-predictive-coding]]'
title: Non-stationary Kernels in GPC
---

**Background:** Generalised predictive coding models often rely on specific kernel functions to approximate marginal distributions of latent variables. The choice and stationarity of these kernels influence the effectiveness of inference in dynamical systems.

**Question / Future Work:** Developing methods to incorporate non-stationary kernels within the online generalised predictive coding framework is a notable challenge. While current implementations assume stationary kernels to ensure analytical tractability, investigating non-stationary alternatives is required to better model systems with changing dynamical properties.

**Why It Matters:** Non-stationary kernels would significantly increase the flexibility of predictive coding models for real-world scenarios where system dynamics are non-homogeneous over time, a critical requirement for robust online inference.

**Evidence:** We note that, whilst initially enticing, a version of ODEM using non-stationary kernels could prove challenging, particularly when deriving the approximate marginal distribution as in Section. 3.1.