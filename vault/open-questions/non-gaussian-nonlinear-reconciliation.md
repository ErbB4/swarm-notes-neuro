---
created_at: '2026-05-02T05:49:29Z'
source_papers:
- '[[openalex-260426668-nonlinear-probabilistic-forecast-reconciliation]]'
title: Non-Gaussian Nonlinear Forecast Reconciliation
---

**Background:** Nonlinear constraints in forecasting often involve variables with non-Gaussian distributions, yet existing reconciliation techniques frequently rely on Gaussian assumptions.

**Question / Future Work:** The extension of nonlinear forecast reconciliation methods to accommodate intermittent, discrete, or mixed-type time series remains an open problem, as current state-of-the-art methods like UKF-based approaches are restricted by Gaussian assumptions.

**Why It Matters:** Many real-world forecasting applications, such as demand or count-based monitoring, involve non-Gaussian variables that render current nonlinear reconciliation techniques inapplicable.

**Evidence:** However, our specific algorithm based on UKF is unsuitable to reconcile intermittent or discrete time series with nonlinear constraints due to its underlying Gaussian assumption.