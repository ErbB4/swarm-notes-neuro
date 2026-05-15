---
created_at: '2026-05-15T06:15:16Z'
source_papers:
- '[[openalex-260511569-dual-temporal-lstm-with-hybrid-attention-for-airline-passeng]]'
title: Cabin-Level PLF Forecasting Bottleneck
---

**Background:** Airline passenger load factor forecasting often relies on aggregate metrics that mask distinct behaviors across cabin classes, such as business versus economy, which have different elasticities and booking curves.

**Question / Future Work:** Investigating the decomposition of dual-temporal models to provide cabin-level or fare-class-specific passenger load factor predictions to enable more granular revenue management.

**Why It Matters:** Moving from aggregate to granular forecasting is a fundamental bottleneck for deploying predictive models in production-grade revenue management systems.

**Evidence:** Extending the proposed framework to produce separate class-wise PLF forecasts would make it directly usable in cabin-level revenue management systems and represents a natural next step.