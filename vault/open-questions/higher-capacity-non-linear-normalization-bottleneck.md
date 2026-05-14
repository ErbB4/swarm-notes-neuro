---
created_at: '2026-05-14T06:08:44Z'
source_papers:
- '[[openalex-260510823-norin-backbone-adaptive-reversible-normalization-for-time-se]]'
title: Expressive Normalization Capacity Limits
---

**Background:** Non-linear reversible normalization is crucial for effective time-series forecasting, yet simple transformations often collapse to linear regimes when trained end-to-end with high-capacity backbones. Current approaches mitigate this via decoupled optimization, but are limited to specific two-parameter shape families.

**Question / Future Work:** Explore more expressive non-linear normalization families beyond two-parameter Johnson SU transforms, such as four-parameter transformations or normalizing flows, to handle complex non-Gaussianities like multimodality or heavy-tailed dynamics.

**Why It Matters:** The capability of the normalization layer bounds the representational flexibility of the entire pipeline; understanding the trade-off between normalization expressivity and optimization stability is vital.

**Evidence:** extreme non-Gaussian distributions—such as intraday financial data with multimodality or strong long-range dependence—may benefit from higher-capacity shape families