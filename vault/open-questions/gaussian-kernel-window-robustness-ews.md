---
created_at: '2026-04-19T05:44:35Z'
source_papers:
- '[[openalex-260415230-on-the-robustness-of-mann-kendall-tests-used-to-forecast-cri]]'
title: Gaussian Kernel EWS Robustness
---

**Background:** Rolling window methods for time series analysis often use overlapping windows, which introduces artificial autocorrelation into the resulting indicator time series. The extent to which Gaussian-kernel weighting mitigates these artifacts in the context of early warning signals for critical transitions remains an open empirical and theoretical question.

**Question / Future Work:** Systematic investigation into whether Gaussian-kernel weighting of rolling windows reduces induced autocorrelation enough to restore the validity of trend detection methods like the Mann-Kendall test in critical transition forecasting.

**Why It Matters:** High type I error rates in EWS detection are often driven by autocorrelation artifacts; finding effective mitigation strategies is crucial for reliable forecasting.

**Evidence:** Another approach to reduce the autocorrelation introduced by the rolling window procedure could consist in estimating EWS indicators using rolling windows in which data are weighted with Gaussian kernels... To the best of our knowledge, this method has not yet been applied in the EWS literature.