---
created_at: '2026-05-14T06:09:33Z'
source_papers:
- '[[openalex-260510822-benchmarking-sensor-fault-robustness-in-forecasting]]'
title: Robustness trade-offs in CPS forecasting
---

**Background:** Cyber-physical system (CPS) forecasting models rely on sensor streams prone to faults like noise, bias, missing data, and temporal misalignment, yet standard benchmarks primarily evaluate models on clean, nominal data.

**Question / Future Work:** It remains unresolved how different forecasting architectures and robustness-improvement methods fundamentally trade off across diverse sensor-fault families—such as value, timing, and availability disturbances—when evaluated using a standardized severity-controlled protocol. Specifically, there is no consensus on which intervention strategies are most effective across distinct CPS forecasting tasks, or how these methods transfer when trained on fault families disjoint from the evaluation scenarios.

**Why It Matters:** Understanding these trade-offs is critical for developing operationally reliable CPS forecasting models, as clean-data performance is often a poor predictor of robustness under realistic sensing failures.