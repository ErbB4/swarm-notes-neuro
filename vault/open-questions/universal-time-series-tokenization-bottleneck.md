---
created_at: '2026-05-10T06:03:40Z'
source_papers:
- '[[openalex-260505736-sdflow-similarity-driven-flow-matching-for-time-series-gener]]'
title: Universal Time-Series Tokenization Bottleneck
---

**Background:** Time series generation commonly employs vector quantization (VQ) with autoregressive models, which are susceptible to exposure bias and sequential error accumulation. Current frameworks typically rely on dataset-specific VQ tokenizers, limiting the potential for cross-domain generalization and unified latent modeling.

**Question / Future Work:** The development of a universal, cross-domain time-series tokenizer with a shared, robust codebook is required to enable non-autoregressive generative models to operate in a unified latent space across diverse, heterogeneous time-series sources.

**Why It Matters:** A universal tokenizer is critical for transitioning from domain-specific generation models to general-purpose time-series foundation models that can leverage cross-domain data scaling.