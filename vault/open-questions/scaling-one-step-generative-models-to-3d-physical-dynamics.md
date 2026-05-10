---
created_at: '2026-05-10T06:04:26Z'
source_papers:
- '[[openalex-260505540-towards-scalable-one-step-generative-modeling-for-autoregres]]'
title: Scaling one-step generative models
---

**Background:** Generative surrogate models for dynamical systems often rely on either multi-step inference, such as diffusion-based denoising, or latent-space compression. 1-NFE (Number of Function Evaluation) models attempt to combine generative modeling with one-step rollout efficiency.

**Question / Future Work:** It remains an open question how generative surrogate models can be scaled to fully three-dimensional systems and multi-scale forecasting settings without sacrificing their one-step inference efficiency. Existing approaches, while successful in 2D benchmarks, require further validation and adaptation to handle the increased dimensionality and complexity of fully 3D physical dynamics.

**Why It Matters:** Scalability to 3D systems is the primary bottleneck for widespread adoption of generative surrogates in real-world fluid dynamics and engineering applications.