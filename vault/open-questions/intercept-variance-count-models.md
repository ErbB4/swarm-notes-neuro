---
created_at: '2026-04-16T05:46:15Z'
source_papers:
- '[[openalex-250915508-modelling-time-series-of-counts-with-hysteresis]]'
title: Intercept parameter variance in count models
---

**Background:** Integer-valued time series models, such as Poisson autoregressive (PAR) and Self-Excited Threshold Poisson autoregressive (SETPAR) models, often exhibit high variance in their parameter estimates, particularly for intercept parameters.

**Question / Future Work:** Investigate the theoretical cause of the observed large variance-to-mean ratio in intercept parameter (omega) estimates across various count time series models, including the PAR, SETPAR, and classical GARCH(1,1) models, which currently lacks a formal explanation in the literature.

**Why It Matters:** Understanding this persistent estimation issue is crucial for improving the robustness and interpretability of count time series models, which are widely used in financial and public health forecasting.