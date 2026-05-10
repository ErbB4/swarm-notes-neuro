---
created_at: '2026-05-10T06:05:07Z'
source_papers:
- '[[openalex-260506541-hedging-memory-horizons-for-non-stationary-prediction-via-on]]'
title: Extensions for memory-hedged aggregation
---

**Background:** Online prediction methods under non-stationary regimes often suffer from a trade-off between the stability provided by long adaptation horizons and the responsiveness of short horizons. Since the optimal adaptation scale is unknown and itself non-stationary, methods must typically commit to a single horizon or rely on internal adaptive filtering mechanisms that may not be robust across regimes.

**Question / Future Work:** Future research is needed to develop extensions of memory-hedging aggregation that handle multivariate targets and structured, non-squared loss functions. Additionally, there is a need to explore the online expansion of the memory-scale grid to adapt to evolving computational or performance requirements, as well as broader empirical evaluations using actively retrained base models rather than static ones.

**Why It Matters:** These extensions would significantly broaden the applicability of online aggregation frameworks to real-world operational environments where targets are multivariate, retraining pipelines are dynamic, and loss functions reflect complex decision costs.