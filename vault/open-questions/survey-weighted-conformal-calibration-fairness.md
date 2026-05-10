---
created_at: '2026-05-10T06:06:10Z'
source_papers:
- '[[openalex-260505562-socio-conformal-calibration-in-complex-survey-data-marginal]]'
title: Fairness in Survey-Weighted Conformal Prediction
---

**Background:** Conformal prediction provides rigorous, distribution-free guarantees of marginal coverage, but these aggregate guarantees often mask significant performance disparities across demographic subgroups, especially in settings with complex survey designs and small subgroup sample sizes. Research in this domain aims to reconcile these marginal guarantees with conditional validity for specific groups.

**Question / Future Work:** The practical utility and reliability of Mondrian conformal prediction for ensuring fairness in survey-weighted settings remains an unresolved issue, particularly regarding the trade-off between subgroup coverage gaps and predictive efficiency when dealing with fragmented, thin calibration cells. Future work is needed to develop design-aware conformal theory that can formally integrate complex survey weights into the calibration process rather than just the evaluation phase, as well as to investigate adaptive or data-driven subgroup selection methods that go beyond predefined, fixed categories.

**Why It Matters:** This is technically important because it addresses the core tension between theoretical validity and empirical fairness in machine learning deployments. Identifying whether and how group-specific calibration can be applied safely in small-sample, survey-weighted settings is crucial for AI governance and policy-oriented applications where demographic equity is required.