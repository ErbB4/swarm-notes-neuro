---
created_at: '2026-04-19T05:44:27Z'
source_papers:
- '[[openalex-260415174-mambasl-exploring-single-layer-mamba-for-time-series-classif]]'
title: Optimal SSM Time-Variance Configuration
---

**Background:** Mamba-based architectures rely on parameters that introduce time variance to selectively update or forget state information. While this selective mechanism is effective in language modeling, its performance impact and optimal configuration—specifically regarding which parameters should be time-variant or time-invariant—remain underexplored for time series classification tasks.

**Question / Future Work:** The optimal configuration of time-variance for the Δ, B, and C parameters in the selective SSM for time series classification is not fully understood. Research is needed to establish a theoretical or practical framework for determining the optimal TI/TV (Time-Invariant/Time-Variant) configuration of these parameters on a per-dataset basis, as empirical evidence suggests this is dataset-dependent.

**Why It Matters:** Identifying the correct balance of time-invariance versus time-variance is critical for adapting Mamba-based models to time series data, where signal properties vary significantly. Misconfiguring these SSM components can impair classification accuracy.