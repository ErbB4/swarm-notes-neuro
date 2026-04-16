---
created_at: '2026-04-16T05:46:09Z'
source_papers:
- '[[openalex-260411529-tempusbench-an-evaluation-framework-for-time-series-forecast]]'
title: Dynamic Forecasting Benchmarking
---

**Background:** Time-series foundation models (TSFMs) are typically evaluated on static benchmark datasets which eventually become part of the models' pretraining corpora, causing data leakage.

**Question / Future Work:** The field requires methodologies for creating dynamic forecasting benchmarks—either through synthetic generation or real-time streaming—to ensure test data remains unseen by foundation models during pretraining.

**Why It Matters:** Data leakage significantly undermines the validity of benchmark performance metrics for time-series foundation models, necessitating a shift toward dynamic, non-stationary test beds.