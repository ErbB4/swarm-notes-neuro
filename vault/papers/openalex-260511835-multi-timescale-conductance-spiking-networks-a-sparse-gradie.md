---
# CSL-compatible fields
title: "Multi-Timescale Conductance Spiking Networks: A Sparse, Gradient-Trainable Framework with Rich Firing Dynamics for Enhanced Temporal Processing"
author:
  - literal: "Alex Fulleda-Garcia"
  - literal: "Saray Soldado-Magraner"
  - literal: "Josep Maria Margarit"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11835"

# Custom fields
paper_id: "2605.11835"
paper_source: "openalex"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "multi-timescale-conductance-spiking-networks"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:16:28Z"
created_at: "2026-05-15T06:16:28Z"
---

# Multi-Timescale Conductance Spiking Networks: A Sparse, Gradient-Trainable Framework with Rich Firing Dynamics for Enhanced Temporal Processing

**Authors**: Alex Fulleda-Garcia, Saray Soldado-Magraner, Josep Maria Margarit
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11835](https://arxiv.org/abs/2605.11835)

## Summary

The paper presents multi-timescale conductance spiking networks, a novel SNN framework that achieves both rich dynamical behaviors and high activity sparsity. By parameterizing neuronal conductances, the model supports direct backpropagation without relying on surrogate gradients, addressing a major bottleneck in SNN training. Evaluation on the Mackey-Glass time-series regression task shows superior performance compared to traditional LIF and AdLIF models while maintaining lower computational overhead.

## Key Contributions

- Introduces a gradient-trainable spiking network architecture using parameterized I-V curves for multi-timescale conductance control.
- Enables direct backpropagation through time without the need for surrogate gradients, improving model trainability for continuous-valued tasks.
- Outperforms baseline LIF and AdLIF networks in Mackey-Glass time-series regression while significantly reducing spike-based computational and communication activity.

## Key Concepts

- [[multi-timescale-conductance-spiking-networks]]: A gradient-trainable spiking neural network framework that achieves rich firing dynamics and high sparsity by parameterizing neuronal conductance timescales.

## Archivist Review

I approved the Multi-timescale Conductance Spiking Networks concept as it introduces a novel, reusable mechanism for enabling direct backpropagation in SNNs via conductance parametrization. I rejected the Mackey-Glass dataset as it is a standard mathematical benchmark rather than a primary empirical data source requiring a vault entry. No new open questions were provided or identified that meet the high standard for permanence.

### Approved Concepts
- Multi-timescale Conductance Spiking Networks: This framework enables direct backpropagation through time in spiking neural networks without surrogate gradients by shaping neuronal I-V curves through multi-timescale conductances.

### Rejected Candidates
- [dataset] Mackey-Glass (`mackey-glass`) - low_impact: This is a standard mathematical benchmark problem for time series, not a distinct, standalone dataset entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.11835)
- [PDF](https://arxiv.org/pdf/2605.11835)

