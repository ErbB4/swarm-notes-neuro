---
created_at: '2026-04-23T05:48:30Z'
source_papers:
- '[[openalex-260417676-subsample-based-estimation-under-dynamic-contamination]]'
title: Robust Model Selection Under Dynamic Contamination
---

**Background:** Robust estimation in dynamic time series is complicated by the propagation of contamination through residual filters. While robust estimation techniques are now being developed to handle these footprints, model selection in such contaminated environments remains poorly understood.

**Question / Future Work:** Investigating the development of propagation-aware information criteria for model selection that are robust to dynamic contamination, extending beyond empirical heuristics like averaged AIC.

**Why It Matters:** Standard information criteria are sensitive to contaminated observations; developing theoretically sound criteria that account for the residual structure is essential for reliable model selection in contaminated time series.

**Evidence:** In particular, the development of subsample-based information criteria tailored to this framework remains an open problem. The average AIC used in the present paper serves only as a practical device, and a principled criterion for contaminated dynamic models with patch removal requires separate analysis.