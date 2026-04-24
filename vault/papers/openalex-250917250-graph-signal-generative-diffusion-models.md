---
# CSL-compatible fields
title: "Graph Signal Generative Diffusion Models"
author:
  - literal: "Yiğit Berkay Uslu"
  - literal: "Samar Hadou"
  - literal: "Sergio Rozada"
  - literal: "Shirin Saeedi Bidokhti"
  - literal: "Alejandro Ribeiro"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.17250"

# Custom fields
paper_id: "2509.17250"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "u-gnn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:55Z"
created_at: "2026-04-24T05:51:55Z"
---

# Graph Signal Generative Diffusion Models

**Authors**: Yiğit Berkay Uslu, Samar Hadou, Sergio Rozada, Shirin Saeedi Bidokhti, Alejandro Ribeiro
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.17250](https://arxiv.org/abs/2509.17250)

## Summary

This paper proposes U-shaped encoder-decoder graph neural networks (U-GNNs) to address stochastic graph signal generation via denoising diffusion processes. The U-GNN architecture incorporates a novel pooling operation based on zero-padding, which allows the network to learn multiscale feature embeddings while preserving the original graph's convolutional structure. By applying this model to stock price forecasting, the authors demonstrate that the diffusion-based approach effectively captures volatility and tail events that are typically missed by deterministic models.

## Key Contributions

- Introduced U-shaped encoder-decoder graph neural networks (U-GNNs) for stochastic generation of graph signals.
- Proposed a pooling mechanism for U-GNNs that utilizes zero-padding to maintain convolutionality with respect to the original graph, avoiding traditional graph coarsening.
- Demonstrated the effectiveness of diffusion-based U-GNNs in probabilistic stock price forecasting, better capturing market uncertainties and tail events compared to deterministic baselines.

## Open Questions & Future Work

- [[integrated-spatio-temporal-diffusion-bottleneck]]

## Key Concepts

- [[u-gnn]]: A U-shaped encoder-decoder graph neural network architecture that employs a zero-padding pooling mechanism to enable multiscale feature extraction while maintaining original graph convolutionality.

## Archivist Review

I approved the U-GNN concept as it introduces a novel approach to multiscale graph signal processing that is likely to see reuse in temporal graph forecasting. The open question was refined to better characterize the structural bottleneck inherent in decoupling space-time modeling in diffusion frameworks.

### Approved Concepts
- U-GNN: Provides a novel architectural approach to multiscale graph representation learning that avoids arbitrary graph coarsening via zero-padding.

### Approved Open Questions
- Integrated Spatio-Temporal Diffusion Bottleneck: The current decoupling of space and time is a fundamental limitation in generative graph modeling, hindering the capacity to capture high-order dependencies in dynamic signals.

### Rejected Candidates
- [open_question] Integrated Spatio-Temporal Diffusion Modeling (`integrated-spatio-temporal-modeling`) - other: Renamed to improve descriptiveness and alignment with vault standards.

## Links

- [Abstract](https://arxiv.org/abs/2509.17250)
- [PDF](https://arxiv.org/pdf/2509.17250)

