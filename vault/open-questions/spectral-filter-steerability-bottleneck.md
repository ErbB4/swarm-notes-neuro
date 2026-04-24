---
created_at: '2026-04-24T05:49:35Z'
source_papers:
- '[[openalex-250820206-filter-then-attend-improving-attention-based-time-series-for]]'
title: Spectral Filter Steerability Bottleneck
---

**Background:** Transformer-based models for time series forecasting exhibit an inherent frequency bias toward low-frequency components, often resulting in oversmoothing of temporal patterns.

**Question / Future Work:** While learnable frequency filters have been shown to mitigate oversmoothing and improve forecasting performance, there is a need to develop more sophisticated, interpretable, and steerable filtering mechanisms that go beyond simple pointwise frequency multiplication to target specific spectral behaviors.

**Why It Matters:** Current frequency filtering techniques are limited to basic implementations; enhancing their steerability and interpretability could lead to significant performance gains and provide better insight into how these models learn temporal dependencies.