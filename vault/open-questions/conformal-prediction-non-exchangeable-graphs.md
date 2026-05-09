---
created_at: '2026-05-09T05:56:47Z'
source_papers:
- '[[openalex-260504957-delving-into-non-exchangeability-for-conformal-prediction-in]]'
title: Conformal Prediction for Graph-Structured Time Series
---

**Background:** Conformal prediction traditionally assumes data exchangeability to provide finite-sample coverage guarantees, which is often violated in complex, coupled, or non-stationary systems such as graph-structured time series.

**Question / Future Work:** Developing robust, model-agnostic conformal prediction frameworks that maintain rigorous coverage guarantees while accounting for joint, system-wide non-exchangeability induced by dynamic spatio-temporal dependencies remains a critical open challenge in uncertainty quantification. Methods often struggle to achieve the optimal balance between maintaining valid coverage and ensuring efficiency in the presence of strong, evolving cross-node couplings.

**Why It Matters:** Addressing this bottleneck is essential for applying reliable, distribution-free uncertainty quantification to high-stakes, graph-structured systems where point forecasts are insufficient.