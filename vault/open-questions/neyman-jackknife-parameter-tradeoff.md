---
created_at: '2026-04-30T06:03:49Z'
source_papers:
- '[[openalex-260424017-neyman-jackknife-design-based-variance-estimation-for-causal]]'
title: Neyman Jackknife parameter optimization
---

**Background:** Design-based variance estimation in causal inference under interference requires balancing the bias of the estimator against the conservativeness of the variance bounds. Current methods often rely on structural assumptions about exposure mappings or specific resampling rules that are not easily tuned.

**Question / Future Work:** Future research is needed to determine the optimal selection of the index-sampling rule and computable proxy within the Neyman Jackknife framework, specifically to minimize the tradeoff between approximation error and estimator inflation for complex, non-IPW estimators.

**Why It Matters:** Characterizing this tradeoff is essential for making the Neyman Jackknife practically effective and providing clear guidelines for hyperparameter selection in diverse experimental designs.

**Evidence:** The fundamental tradeoff of our framework, however, is that increasing the size of S makes the approximation of E[τ^|S,W−S] more difficult.