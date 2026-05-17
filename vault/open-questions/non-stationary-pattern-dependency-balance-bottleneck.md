---
created_at: '2026-05-17T06:07:11Z'
source_papers:
- '[[openalex-260514551-seesawnet-towards-non-stationary-time-series-forecasting-wit]]'
title: Non-stationary Pattern Dependency Balance
---

**Background:** Time series data often exhibits non-stationarity, leading to distributional shifts that vary by instance and temporal regime. Instance normalization is widely used to align these distributions, but it simultaneously risks suppressing instance-specific structural information.

**Question / Future Work:** Further research is needed to characterize the optimal balance between common dependency learning (typically achieved through normalization) and instance-specific dependency preservation across varying non-stationary structures, such as trend shifts, volatility changes, or structural breaks. Developing theoretical frameworks for this balance is critical for advancing robust non-stationary forecasting.

**Why It Matters:** This is essential for designing more robust forecasting models that do not rely on static assumptions about normalization, as different types of non-stationarity likely require distinct strategies for balancing common and specific signals.