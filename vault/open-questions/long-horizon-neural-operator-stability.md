---
created_at: '2026-04-17T05:47:03Z'
source_papers:
- '[[openalex-260412794-stable-fine-time-step-long-horizon-turbulence-prediction-wit]]'
title: Long-horizon Neural Operator Stability
---

**Background:** Neural operator-based autoregressive forecasting in chaotic dynamical systems (such as turbulence) often suffers from error accumulation that degrades long-term statistical fidelity at fine temporal resolutions.

**Question / Future Work:** Development of training objectives that enforce compositional consistency across different temporal strides is required to prevent divergence in long-horizon neural operator rollouts. This includes exploring how to optimize routing mechanisms and expert configurations to ensure accuracy across varied temporal scales and chaotic regimes.

**Why It Matters:** Crucial for the long-term reliability of surrogates in scientific computing where statistical accuracy is as important as point-wise error.

**Evidence:** Future work includes... multi-step objectives that enforce compositional consistency across strides, and systematic measurement of accuracy and efficiency as routing budgets vary.