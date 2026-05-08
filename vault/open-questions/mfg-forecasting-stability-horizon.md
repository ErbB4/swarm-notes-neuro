---
created_at: '2026-05-08T05:43:46Z'
source_papers:
- '[[openalex-250608465-forecasting-public-sentiments-via-mean-field-games]]'
title: Forecasting stability horizon limits
---

**Background:** Mean Field Games (MFG) are modeled using systems of coupled nonlinear partial differential equations where value functions and density functions evolve in opposite directions of time. Forecasting future states of such systems is inherently unstable because it resembles a time-reversed heat equation.

**Question / Future Work:** The proposed convexification method achieves global convergence for a specific finite time horizon, but the problem exhibits inherent numerical instability for longer time durations. Characterizing the stability bounds and developing stabilization strategies for long-horizon MFG-based forecasting remains an unresolved challenge.

**Why It Matters:** Determining stability limits for MFG-based forecasting is essential for ensuring reliable predictions in dynamic systems where behavior can diverge or blow up over time.

**Evidence:** We observe numerically that the convexification method can predict the solution of the MFG system accurately up to time T=1... We can see that both the predicted solution and the relative cost behave badly for t > 1.