---
created_at: '2026-04-30T06:02:37Z'
source_papers:
- '[[openalex-260423968-decompkan-decomposed-patch-kan-for-long-term-time-series-for]]'
title: Mapping KAN Latents to Features
---

**Background:** In Kolmogorov–Arnold Network (KAN) architectures, each edge represents a learnable 1D function over latent coordinates, allowing for direct visualization of learned nonlinearities. However, these latent representations are computed on transformed patch embeddings rather than raw input variables.

**Question / Future Work:** There is a need for robust attribution methods that can map the visually inspectable 1D nonlinearities learned by KAN edge functions back to raw, human-interpretable input variables. While the functional form itself is inspectable, its current representation in latent space obscures the direct mechanistic interpretation of how raw physical variables interact within the model.

**Why It Matters:** Bridging the gap between 'latent-space inspectability' and 'feature-space interpretability' is critical for scientific validity, ensuring that identified patterns correspond to physical phenomena in the raw time series.