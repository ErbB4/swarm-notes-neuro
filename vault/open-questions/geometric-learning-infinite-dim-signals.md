---
created_at: '2026-05-10T06:05:59Z'
source_papers:
- '[[openalex-260506395-consistent-geometric-deep-learning-via-hilbert-bundles-and-c]]'
title: Geometric Learning for Infinite-Dimensional Signals
---

**Background:** Deep learning architectures often operate on signals supported on manifolds, but current methods struggle with infinite-dimensional signals such as time series or probability distributions. Existing geometric learning frameworks generally assume finite-dimensional fiber representations and rely on fixed connections.

**Question / Future Work:** Establishing a unified theory and convolutional framework for operating directly on infinite-dimensional signals supported on manifolds, such as sections of a Hilbert bundle, is needed to ensure robustness to discretization and scalability. Extending convergence results for discrete graph-based Laplacians to the infinite-dimensional Hilbert bundle setting remains a major theoretical bottleneck for ensuring consistent performance across varying data resolutions.

**Why It Matters:** Addressing this gap is necessary to provide theoretical guarantees, such as consistency and transferability, for deep learning models operating on complex data structures like time series and measure-valued representations.

**Evidence:** The main technical reason behind this gap is the lack of an extension of the convergence result... to bundles with infinite-dimensional fibers.