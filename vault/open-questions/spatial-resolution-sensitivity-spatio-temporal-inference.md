---
created_at: '2026-05-02T05:50:16Z'
source_papers:
- '[[openalex-260426535-arma-approximation-of-a-non-separable-spatio-temporal-model]]'
title: Spatial resolution sensitivity analysis
---

**Background:** Spatio-temporal Gaussian random field models based on stochastic partial differential equations can be discretized to facilitate parameter inference and prediction. However, applying these models to large, complex datasets often reveals sensitivities to spatial resolution that are not fully understood.

**Question / Future Work:** The observed sensitivity of cross-validation prediction scores to spatial resolution in non-separable spatio-temporal models remains an unresolved issue, particularly for higher spatial resolutions where parameter inference can exhibit numerical instabilities or potentially unrealistic temporal range estimates. Clarifying the origin of this resolution-dependence—whether it arises from numerical errors, model misspecification, or overfitting—is a necessary next step for robust model application.

**Why It Matters:** Understanding the relationship between spatial discretization density and predictive stability is critical for the reliable deployment of these models in automated or high-stakes environmental forecasting tasks.

**Evidence:** Specifically, the model has a tendency to overestimate the temporal range when the number of spatial basis functions grows large, with detrimental effect on predictions.