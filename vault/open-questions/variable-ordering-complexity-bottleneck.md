---
created_at: '2026-05-03T06:02:12Z'
source_papers:
- '[[openalex-260427814-probabilistic-circuits-for-irregular-multivariate-time-serie]]'
title: Variable Ordering Complexity Bottleneck
---

**Background:** In multivariate probabilistic models where joint distributions are decomposed sequentially, the choice of variable ordering can drastically alter the learned dependency structure.

**Question / Future Work:** Identifying optimal variable or channel ordering for structures like Sum-Product Networks (SPNs) or autoregressive factorizations is often computationally intractable due to factorial complexity, yet current heuristics remain sub-optimal for high-dimensional or heterogeneous data.

**Why It Matters:** This is a fundamental limitation for any structural probabilistic forecasting model that relies on sequential variable decomposition, affecting both accuracy and generalizability.

**Evidence:** While the sequential structure of the SPN implies that the order theoretically influences the modeled joint density, identifying an optimal order is computationally intractable due to the C! possible permutations.