---
created_at: '2026-05-14T06:09:16Z'
source_papers:
- '[[openalex-260510179-one-step-graph-structured-neural-flows-for-irregular-multiva]]'
title: Learning Time-Varying Interaction Graphs
---

**Background:** Continuous-time models for irregular multivariate time series often assume static inter-variable interaction structures. The development of methods capable of representing time-varying dependencies remains an active area of research for non-stationary systems.

**Question / Future Work:** The current approach relies on an interaction graph inferred from local temporal segments, which is then marginalized into a single time-invariant graph for the generative model. Extending this framework to learn time-varying interaction graphs is necessary to model non-stationary dynamics accurately, as static graphs fail to capture the evolution of dependencies over long, complex observation sequences.

**Why It Matters:** This is a critical limitation because real-world physical and clinical systems often exhibit dependencies that shift in response to events or temporal state changes, rendering static graph assumptions insufficiently expressive.

**Evidence:** Future work will extend GSNF to time-varying interaction graphs, enabling dynamically evolving dependencies in non-stationary systems.