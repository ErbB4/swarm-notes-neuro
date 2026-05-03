---
created_at: '2026-05-03T06:03:07Z'
source_papers:
- '[[openalex-260428163-sequential-inference-for-gaussian-processes-a-signal-process]]'
title: Scalable nonstationary sequential GPs
---

**Background:** While exact Gaussian process inference exhibits cubic computational complexity with respect to data size, modern approximations seek to achieve scalable and online inference through methods such as basis expansions, Markovian state-space models, and sparse variational approaches. These methods convert the complicated function-space inference into parametric forms, yet they often depend on stationary kernels or limited basis functions, which restrict their expressiveness in high-dimensional or strongly nonstationary systems.

**Question / Future Work:** There is a critical need to develop sequential Gaussian process algorithms that can handle high-dimensional and strongly nonstationary environments. Current methods rely heavily on stationary kernels, which may not capture the complex, evolving structures in real-world signal processing tasks. Future work should focus on integrating more flexible, data-driven kernel parameterizations—potentially leveraging neural feature maps or deep kernel learning—while maintaining the analytical tractability and uncertainty quantification properties of Bayesian inference.

**Why It Matters:** This is a fundamental bottleneck for deploying GP-based sequential estimation in real-world applications where the underlying signal dynamics are inherently nonstationary and high-dimensional. Bridging this gap is essential to make GPs competitive with modern neural architectures.