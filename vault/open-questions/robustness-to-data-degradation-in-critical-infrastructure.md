---
created_at: '2026-05-14T06:10:26Z'
source_papers:
- '[[openalex-260510592-a-resilient-solution-for-sewer-overflow-monitoring-across-cl]]'
title: Robustness to data degradation
---

**Background:** Sewer monitoring systems frequently face data quality issues including sensor signal outliers and missing observations due to maintenance cycles or infrastructure faults.

**Question / Future Work:** Existing resilient monitoring frameworks often assume clean or interpolated input data, leaving the impact of noisy, corrupted, or inconsistently missing sensor data on downstream forecasting and risk assessment largely uncharacterized. Future research needs to establish robustness metrics and error-handling strategies that ensure forecasting reliability under realistic, non-ideal data conditions.

**Why It Matters:** Ensuring model robustness against real-world sensor degradation is critical for preventing false positives or missed overflow warnings in safety-critical infrastructure.

**Evidence:** Future work will extend the demonstrator toward live data integration and broader robustness analysis, such as outliers or missing values.