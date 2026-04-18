---
created_at: '2026-04-18T05:34:41Z'
source_papers:
- '[[openalex-260413604-irregularly-sampled-time-series-interpolation-for-binary-evo]]'
title: Morphology-Aware Neighbor Selection
---

**Background:** Interpolation of sparse, irregularly sampled physical simulation trajectories often relies on selecting a fixed number of neighboring data points in parameter space. Such fixed-neighbor approaches struggle to balance coverage and local accuracy, particularly when data points exhibit disparate morphologies or sensitive responses to initial conditions.

**Question / Future Work:** Developing dynamic or adaptive neighbor selection strategies that account for morphological similarity—rather than simple geometric distance—remains a critical hurdle in improving interpolation fidelity in high-dimensional physical parameter spaces. This includes handling variable neighbor counts and incorporating similarity-weighted barycentric schemes to avoid physical artifacts.

**Why It Matters:** This is a fundamental limitation in surrogate modeling and emulation for expensive scientific simulations, where sparse data often forces the inclusion of unrepresentative 'neighboring' samples.

**Evidence:** Future work could explore alternative weighting schemes that can accommodate variable numbers of neighbors or incorporate morphological similarity metrics into the neighbor selection process.