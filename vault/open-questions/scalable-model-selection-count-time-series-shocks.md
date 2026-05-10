---
created_at: '2026-05-10T06:03:33Z'
source_papers:
- '[[openalex-260506168-scalable-model-selection-for-count-time-series-with-structur]]'
title: Scalable Model Selection for Count Time Series with Shocks
---

**Background:** Healthcare activity data often exhibit dependencies on past observations, overdispersion, and vulnerability to sudden, system-wide disruptions such as pandemics. Existing models for count time series frequently rely on simplistic assumptions that fail to adequately characterize or predict the dynamics of such processes during and after major shocks.

**Question / Future Work:** There is a need for robust, scalable model selection frameworks for count time series that can effectively address regime shifts and structural breaks. Future research should prioritize balancing predictive accuracy with computational feasibility in high-dimensional model selection portfolios, while moving toward explicit causal designs that decompose the drivers of shifts rather than relying on pragmatic indicator variables.

**Why It Matters:** This reflects a critical methodological bottleneck in applying time-series analysis to non-stationary count data, where intervention indicators often serve as opaque proxies for complex dynamical shifts. Improving these frameworks is essential for reliable decision-making in healthcare and other systemically sensitive domains.