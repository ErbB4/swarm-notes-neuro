---
created_at: '2026-05-17T06:07:59Z'
source_papers:
- '[[openalex-260514642-distributionally-robust-model-predictive-control-for-virtual]]'
title: Joint Wasserstein Ambiguity Sets
---

**Background:** Model Predictive Control (MPC) often relies on stage-wise forecasts that ignore temporal dependencies between uncertain variables over the control horizon. In systems with energy storage, such as Virtual Power Plants (VPPs), optimal control depends on the joint trajectory of these variables rather than marginal distributions at each individual time step.

**Question / Future Work:** The independent stage-wise construction of Wasserstein ambiguity sets fails to capture temporal dependencies in the electricity price process. Future research is required to construct joint Wasserstein ambiguity sets over price trajectories to prevent overly conservative robustification of intertemporal arbitrage decisions in storage-coupled systems.

**Why It Matters:** In VPPs with battery storage, decisions at time 'k' influence the state at 'k+1'. If the controller does not account for the joint evolution of price distributions, it may implement overly conservative strategies that ignore profitable, multi-period arbitrage opportunities.

**Evidence:** Although the underlying quantile forecasts are generated jointly by the same model conditioned on a common lookback window, the resulting ambiguity sets are constructed independently at each prediction step... temporal dependencies in the price process are therefore not explicitly captured.