---
# CSL-compatible fields
title: "SDFlow: Similarity-Driven Flow Matching for Time Series Generation"
author:
  - literal: "Wei Li"
  - literal: "Shibo Feng"
  - literal: "Pengcheng Wu"
  - literal: "Min Wu"
  - literal: "Peilin Zhao"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05736"

# Custom fields
paper_id: "2605.05736"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-generation"
  - "flow-matching"
  - "vector-quantization"
  - "latent-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sdflow-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:03:40Z"
created_at: "2026-05-10T06:03:40Z"
---

# SDFlow: Similarity-Driven Flow Matching for Time Series Generation

**Authors**: Wei Li, Shibo Feng, Pengcheng Wu, Min Wu, Peilin Zhao
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05736](https://arxiv.org/abs/2605.05736)

## Summary

SDFlow is a non-autoregressive framework designed to address the exposure bias and error accumulation prevalent in traditional autoregressive time-series generation models. By operating within a frozen VQ latent space, the model utilizes flow matching to enable parallel sequence generation rather than sequential token prediction. Key innovations include a low-rank manifold decomposition for dimensionality reduction and a variational flow-matching formulation to incorporate discrete supervision. The approach demonstrates superior generation quality and faster inference speeds compared to current state-of-the-art autoregressive methods.

## Key Contributions

- Eliminates exposure bias in time-series generation by replacing autoregressive token prediction with a non-autoregressive global transport map.
- Reduces latent space dimensionality via low-rank manifold decomposition and a learned anchor prior for more efficient training and inference.
- Achieves state-of-the-art performance on discriminative and fidelity metrics while providing significant inference speedups over autoregressive baselines.

## Open Questions & Future Work

- [[universal-time-series-tokenization-bottleneck]]

## Key Concepts

- [[sdflow-framework]]: A non-autoregressive time-series generation framework that uses flow matching on frozen VQ latent spaces to eliminate exposure bias.

## Archivist Review

I approved the SDFlow framework as it represents a meaningful shift toward non-autoregressive generation in time series, a domain historically dominated by autoregressive VQ approaches. I also approved the open question regarding universal tokenizers, as this reflects a fundamental architectural limitation for scaling generative models beyond single-dataset benchmarks. Minor naming adjustments were made to ensure the vault remains organized and consistent with existing nomenclature.

### Approved Concepts
- Similarity-Driven Flow Matching (SDFlow): Moves time-series generation away from autoregressive VQ-VAE token modeling toward a parallelizable non-autoregressive flow matching paradigm, directly mitigating exposure bias.

### Approved Open Questions
- Universal Time-Series Tokenization Bottleneck: A universal tokenizer is critical for transitioning from domain-specific generation models to general-purpose time-series foundation models that can leverage cross-domain data scaling.

### Rejected Candidates
- [concept] SDFlow (`sdflow`) - duplicate_existing: Renamed to sdflow-framework for consistency with naming conventions and to avoid ambiguity with the paper title.
- [open_question] Developing Universal Time-Series Tokenizers (`universal-time-series-tokenizer`) - duplicate_existing: Renamed to universal-time-series-tokenization-bottleneck for better alignment with existing architectural bottleneck research tracks in the vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.05736)
- [PDF](https://arxiv.org/pdf/2605.05736)

