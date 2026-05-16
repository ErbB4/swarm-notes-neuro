---
created_at: '2026-05-16T06:01:03Z'
source_papers:
- '[[openalex-260513678-three-stage-learning-unlocks-strong-performance-in-simple-mo]]'
title: Adaptive Normalization Strength Selection
---

**Background:** Normalization methods in long-term time series forecasting, such as Reversible Instance Normalization (RevIN), aim to mitigate distribution shift by removing local mean and variance, but these statistics often contain predictive state information.

**Question / Future Work:** Developing methods that can automatically determine the optimal degree of local statistic removal, balancing the mitigation of non-stationarity with the preservation of useful predictive state information, remains a fundamental challenge in time series preprocessing.

**Why It Matters:** This represents a core trade-off in forecasting: removing non-stationarity while retaining signal, which is critical for model generalizability.

**Evidence:** How to automatically select an appropriate normalization strength remains an open problem.