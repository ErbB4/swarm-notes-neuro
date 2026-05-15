---
created_at: '2026-05-15T06:15:29Z'
source_papers:
- '[[openalex-260512200-investigating-simple-target-covariate-relationships-for-chro]]'
title: Unified Temporal-Tabular Foundation Architectures
---

**Background:** Time series foundation models often rely on distinct architectural paradigms for modeling temporal dynamics versus in-context covariate regression. Achieving robust integration of both capabilities is essential for models deployed in scenarios with rich exogenous information.

**Question / Future Work:** Developing a unified foundation model architecture that effectively synthesizes explicit temporal dependency modeling (e.g., autoregressive forecasting) with robust in-context tabular regression capabilities remains an unresolved challenge for comprehensive covariate-aware forecasting.

**Why It Matters:** Current time series foundation models typically excel at either univariate temporal modeling or feature-target regression, creating a performance gap in domains where both patterns are crucial for accuracy.

**Evidence:** In particular, a foundation architecture that combines explicit temporal dependency modeling, as in Chronos-2, with in-context regression capabilities inspired by TabPFN-TS, could represent an interesting direction for covariate-aware time series foundation models.