---
created_at: '2026-04-24T05:52:18Z'
source_papers:
- '[[openalex-250920460-differential-privacy-of-network-parameters-from-a-system-ide]]'
title: Optimal Noise Covariance Design
---

**Background:** The privacy protection of a graph shift operator (GSO) against system identification attacks depends on the design of the noise covariance structure in differentially private inputs.

**Question / Future Work:** It remains unresolved how to optimally design the covariance structure of noise in differentially private excitation signals to maximize privacy guarantees for the graph shift operator while maintaining utility, particularly in cases where the graph filter is non-invertible or the noise must account for temporal and spatial correlations inherent in complex systems. Developing such optimal mechanisms involves navigating the trade-off between the condition number of the noise covariance and the restrictions on input data correlations.

**Why It Matters:** This is a fundamental challenge in balancing privacy utility and data statistical properties, as current approaches identify the potential for 'privacy for free' but note the restrictive nature of the required noise structure in real-world scenarios.