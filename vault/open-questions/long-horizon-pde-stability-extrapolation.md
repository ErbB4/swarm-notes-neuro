---
created_at: '2026-05-14T06:10:00Z'
source_papers:
- '[[openalex-260510154-stable-long-horizon-pde-forecasting-via-latent-structured-sp]]'
title: Stability in Long-Horizon Forecasting
---

**Background:** In data-driven PDE forecasting, models are often trained on limited time horizons and deployed autoregressively for long-range predictions, leading to cumulative error growth and divergence from the physical solution manifold.

**Question / Future Work:** There is an unresolved challenge in ensuring that learned latent propagators maintain long-term structural stability and generalization beyond the specific temporal range seen during training. While specific structural biases like spectral decomposition can help, it remains an open question how to design latent propagation laws that remain robust across varying initial conditions and increasingly long, unseen extrapolation horizons without requiring exhaustive supervision across the entire long-term trajectory.

**Why It Matters:** Long-horizon forecasting is essential for scientific utility, and the current reliance on finite-time supervision makes generalization to long-time dynamics a significant bottleneck in deploying neural surrogates for real-world physical systems.