---
created_at: '2026-05-03T06:03:22Z'
source_papers:
- '[[openalex-260427443-abc-any-subset-autoregression-via-non-markovian-diffusion-br]]'
title: Non-Markovian History Compression Bottleneck
---

**Background:** Continuous-time diffusion models frequently employ standard transformer architectures that attend to the entire history, which limits scalability for high-frequency or long-duration temporal processes.

**Question / Future Work:** Developing efficient architectures, such as state-space models, to selectively compress path history in non-Markovian generative models remains an unresolved challenge for maintaining computational feasibility.

**Why It Matters:** Addressing the computational overhead of path-dependent history is critical for the application of non-Markovian generative models to long-range forecasting.

**Evidence:** For a mathematically faithful implementation, we made the transformer network attend to the entire history, but there are efficient architectures (e.g., SSMs) that selectively compress the history...