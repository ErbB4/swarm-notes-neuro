---
created_at: '2026-04-24T05:51:28Z'
source_papers:
- '[[openalex-260419442-state-forecasting-in-an-estimation-framework-with-surrogate]]'
title: Double dipping bias in hybrid estimation
---

**Background:** State estimation frameworks often rely on data-driven surrogate models to augment physics-based models when observations are partial or intermittent. A significant challenge in these hybrid architectures is the potential for statistical bias when the surrogate model is iteratively updated using the same data that was previously used to inform the state estimates.

**Question / Future Work:** There is a need to develop a rigorous mathematical framework to address potential biases, often referred to as "double dipping," that arise when surrogate models are iteratively retrained using data that has already been processed through an estimation framework. Determining how to correctly decouple the learning and estimation steps to prevent overfitting or the introduction of correlated errors remains a key open problem.

**Why It Matters:** This is crucial for the statistical integrity of hybrid data-driven/physics-based estimation systems, where failing to address circular dependency can lead to overconfident or biased state estimates.