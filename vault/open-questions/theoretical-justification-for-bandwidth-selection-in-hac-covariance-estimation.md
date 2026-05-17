---
created_at: '2026-05-17T06:07:20Z'
source_papers:
- '[[openalex-260514491-adaptive-long-run-variance-thresholding-for-sparse-covarianc]]'
title: Theoretical justification for bandwidth selection
---

**Background:** High-dimensional covariance estimation in time series requires data-driven bandwidth selection for long-run variance, which currently lacks a rigorous theoretical justification within many proposed frameworks.

**Question / Future Work:** A formal theoretical justification for the bandwidth selection procedure used in adaptive long-run variance thresholding for autocorrelated high-dimensional data is needed to ensure the consistency and optimality of the thresholding estimator.

**Why It Matters:** The selection of regularization and bandwidth parameters is critical for the robustness of high-dimensional sparse estimators, yet this remains a common heuristic gap in statistical literature.

**Evidence:** Although we do not provide a theoretical justification for this data-driven procedure, our numerical studies show that it performs reasonably well.