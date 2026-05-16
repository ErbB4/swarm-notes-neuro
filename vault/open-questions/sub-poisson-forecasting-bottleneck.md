---
created_at: '2026-05-16T06:01:39Z'
source_papers:
- '[[openalex-260512992-spikeprophecy-a-large-scale-benchmark-for-autoregressive-neu]]'
title: Sub-Poisson forecasting bottleneck
---

**Background:** In neural spike-count forecasting, sub-Poisson neurons exhibit regular firing patterns that are consistently harder to predict than super-Poisson neurons, creating a baseline noise floor for evaluation.

**Question / Future Work:** Further research is needed to determine whether sub-Poisson predictability limitations arise from intrinsic single-cell biophysics or metric artifacts, and to develop dispersion-aware metrics that decouple these factors.

**Why It Matters:** Identifying the root of the sub-Poisson noise floor is essential for accurately assessing predictive progress in neural forecasting and avoiding metric-induced bias.

**Evidence:** These neurons therefore impose a hard noise floor on aggregate metrics: ~0.07 regardless of model quality.