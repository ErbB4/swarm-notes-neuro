---
created_at: '2026-04-30T06:02:46Z'
source_papers:
- '[[openalex-260424041-end-to-end-learning-for-partially-observed-time-series-with]]'
title: End-to-End POTS Integration
---

**Background:** Partially-observed time series (POTS) often involve fragmented analysis workflows where data imputation and downstream predictive modeling are treated as independent tasks.

**Question / Future Work:** The research community lacks standardized methodologies for training unified, end-to-end learning architectures that jointly optimize missing-value handling and downstream predictive tasks (e.g., forecasting, classification). Investigating these integrated frameworks is essential for reducing error propagation and improving the robustness of predictive models in real-world scenarios with incomplete data.

**Why It Matters:** Addressing the coupling of imputation and prediction is critical for creating reliable ML models that can function effectively when missing data is a pervasive characteristic rather than a distinct preprocessing step.

**Evidence:** Dealing with incomplete data often leads to fragmented workflows where imputation and downstream predictive tasks are entirely decoupled, resulting in suboptimal performance, limited reusability, and error propagation.