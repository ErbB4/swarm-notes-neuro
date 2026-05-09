---
# CSL-compatible fields
title: "FLUID: Continuous-Time Hyperconnected Sparse Transformer for Sink-Free Learning"
author:
  - literal: "Waleed Razzaq"
  - literal: "Yun-Bo Zhao"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04421"

# Custom fields
paper_id: "2605.04421"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "liquid-attention-network"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:58:32Z"
created_at: "2026-05-09T05:58:32Z"
---

# FLUID: Continuous-Time Hyperconnected Sparse Transformer for Sink-Free Learning

**Authors**: Waleed Razzaq, Yun-Bo Zhao
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04421](https://arxiv.org/abs/2605.04421)

## Summary

FLUID addresses the inherent discretization of the scaled-dot-product-attention (SDPA) mechanism by embedding continuous-time dynamics directly into the attention process. It introduces Liquid Attention Network (LAN), which models attention logits as solutions to linear ODEs, and replaces standard residual connections with adaptive Liquid Hyper-Connections. The framework demonstrates improved generalization under distribution shifts, noise robustness, and superior performance on irregular time-series and physical control tasks compared to traditional continuous-time baselines.

## Key Contributions

- FLUID, a continuous-time transformer that integrates Liquid Attention Network (LAN) to replace discrete scaled-dot-product-attention with ODE-based dynamics.
- LAN provides stability guarantees and an explicit attention-sink gate, enabling it to function as a unified bridge between standard Transformers and CT-RNNs.
- Liquid Hyper-Connections improve information regulation compared to standard residuals, leading to up to 47% performance gains across time-series, control, and physical dynamics tasks.

## Open Questions & Future Work

- [[stochastic-lan-ode]]

## Key Concepts

- [[liquid-attention-network]]: A continuous-time attention mechanism that formulates attention logits as the solution to an input-dependent linear ODE.

## Archivist Review

The Liquid Attention Network (LAN) is approved as it provides a foundational shift from discrete SDPA to ODE-based continuous attention, a mechanism likely to influence future temporal models. Liquid Hyper-Connections were rejected as they are secondary to the core innovation, and the second open question was rejected for being less critical than the stochastic formulation research direction.

### Approved Concepts
- Liquid Attention Network (LAN): LAN fundamentally replaces standard discrete attention with continuous dynamical systems, which is the core novelty for addressing long-range and irregular modeling.

### Approved Open Questions
- Stochastic Liquid Attention Networks: This transition could significantly improve the robustness and reliability of the model in real-world applications where data is noisy or stochastic in nature.

### Rejected Candidates
- [concept] Liquid Hyper-Connections (`liquid-hyper-connections`) - subcomponent_of_broader_mechanism: This appears to be a minor architectural modification of residual connections that lacks the standalone transformative impact of the core LAN mechanism.
- [open_question] Manifold-Constrained Hyper-Connections (`manifold-constrained-hyper-connections`) - low_impact: This is a relatively speculative extension of the residual connection concept and does not represent a core unresolved structural bottleneck in time-series modeling.

## Links

- [Abstract](https://arxiv.org/abs/2605.04421)
- [PDF](https://arxiv.org/pdf/2605.04421)

