---
created_at: '2026-05-03T06:02:28Z'
source_papers:
- '[[openalex-260428149-explainable-load-forecasting-with-covariate-informed-time-se]]'
title: Efficient SHAP for TSFMs
---

**Background:** Time Series Foundation Models (TSFMs) are typically treated as black-box models, and post-hoc explainability methods like SHAP are computationally intensive to compute for these architectures.

**Question / Future Work:** The proposed SHAP-based explainability approach for TSFMs relies on evaluating all combinations of feature groupings, which scales poorly as the number of groupings increases. Further research is needed to develop methods for estimating SHAP values from subsets of feature group combinations instead of exhaustively evaluating all coalitions, particularly to enable finer-grained temporal resolution.

**Why It Matters:** Developing more efficient SHAP computation methods is critical for the practical deployment of high-performance TSFMs in real-time, resource-constrained energy infrastructure monitoring.