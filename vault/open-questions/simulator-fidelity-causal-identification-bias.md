---
created_at: '2026-05-14T06:09:26Z'
source_papers:
- '[[openalex-260509870-intervention-based-time-series-causal-discovery-via-simulato]]'
title: Simulator Fidelity in Causal Discovery
---

**Background:** Physics-based simulators used as surrogate models for causal discovery often have imperfect fidelity, representing the distance between simulated and true interventional distributions. This inherent bias affects the identification of causal structures and parameter estimates.

**Question / Future Work:** Future research is needed to rigorously decompose the end-to-end estimation error of causal discovery frameworks that rely on simulators. Specifically, it is critical to determine the sensitivity of causal structural identification to simulator fidelity, including quantifying the regimes where estimated causal effects suffer from sign-reversal.

**Why It Matters:** Fundamental for ensuring the validity of AI-for-Science causal discovery workflows, particularly when high-fidelity models are computationally expensive.

**Evidence:** The simulator fidelity δS... controls both the sample complexity and the sign of the recovered effects.