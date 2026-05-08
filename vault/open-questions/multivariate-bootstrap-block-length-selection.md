---
created_at: '2026-05-08T05:43:38Z'
source_papers:
- '[[openalex-260503997-uncertainty-quantification-in-forecast-comparisons]]'
title: Multivariate Bootstrap Block Selection
---

**Background:** The moving block bootstrap is standard for quantifying uncertainty in time series, yet its performance is sensitive to the choice of block length.

**Question / Future Work:** There is currently a lack of principled, data-driven methods for selecting block lengths in multivariate bootstrap applications, which complicates the automation and robustness of uncertainty quantification in complex forecasting benchmarks. Future work should focus on developing automated selection procedures that adapt to the underlying dependence structure of the data.

**Why It Matters:** Establishing objective criteria for block length selection is necessary to transition from heuristic-based bootstrap implementations to robust, plug-and-play statistical tools.

**Evidence:** data-driven block length selection for the moving block bootstrap remains an open problem in the multivariate setting.