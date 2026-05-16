---
# CSL-compatible fields
title: "Toward AI-Driven Digital Twins for Metropolitan Floods: A Conditional Latent Dynamics Network Surrogate of the Shallow Water Equations"
author:
  - literal: "Phillip Si"
  - literal: "Yuan Qiu"
  - literal: "Omar Sallam"
  - literal: "Jeremy Feinstein"
  - literal: "Ziang He"
  - literal: "Eugene Yan"
  - literal: "Peng Chen"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13761"

# Custom fields
paper_id: "2605.13761"
paper_source: "openalex"
domain: "time-series"
tags:
  - "physics-informed-lstm"
  - "neural-parameterized-markov-operator"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cldnet-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:02:36Z"
created_at: "2026-05-16T06:02:36Z"
---

# Toward AI-Driven Digital Twins for Metropolitan Floods: A Conditional Latent Dynamics Network Surrogate of the Shallow Water Equations

**Authors**: Phillip Si, Yuan Qiu, Omar Sallam, Jeremy Feinstein, Ziang He, Eugene Yan, Peng Chen
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13761](https://arxiv.org/abs/2605.13761)

## Summary

This paper introduces the Conditional Latent Dynamics Network (CLDNet) to accelerate metropolitan flood forecasting by acting as a surrogate for the shallow water equations. CLDNet utilizes a latent neural ODE to capture rainfall-driven dynamics and a coordinate-based decoder conditioned on terrain features to reconstruct hydraulic states without reliance on fixed grids. Evaluated on the Des Plaines River basin, the model achieves a 115x speedup over numerical solvers while providing superior accuracy and flexibility for irregular geographic domains compared to standard grid-based deep learning baselines.

## Key Contributions

- Introduces CLDNet, a conditional latent neural ODE surrogate for shallow water equations that enables grid-independent urban flood modeling.
- Achieves a 115x speedup compared to GPU-accelerated solvers, reducing 96-hour simulations from ~55 minutes to ~29 seconds.
- Outperforms grid-based baselines (VAE-ConvLSTM, FNO) on irregular watershed benchmarks, attaining an 86% critical success index for inundation forecasting.

## Open Questions & Future Work

- [[operational-digital-twin-integration]]

## Key Concepts

- [[cldnet-framework]]: A neural ODE-based surrogate for hydrodynamic simulation that uses coordinate-based decoding to enable grid-independent, high-resolution flood forecasting.

## Archivist Review

I have approved the CLDNet framework as a distinct, reusable architectural paradigm for physics-informed surrogate modeling. I have also approved the open question regarding operational digital twin integration, as it identifies a systemic challenge in transitioning from static inference to active, data-assimilated digital twins. Other candidates were rejected as either too specific to the implementation or insufficiently novel for a permanent knowledge vault.

### Approved Concepts
- Conditional Latent Dynamics Network (CLDNet): The architecture innovatively decouples spatial grid requirements from hydrodynamic surrogate modeling, a significant shift for physics-informed machine learning on irregular domains.

### Approved Open Questions
- Operational Digital Twin Integration: Bridging the gap between surrogate inference and real-time state estimation is necessary to transform surrogate models into functional, operational digital twins.

### Rejected Candidates
- [open_question] Improving Discharge Field Accuracy (`improving-discharge-field-accuracy`) - low_impact: While technically valid, this is a specific performance improvement task rather than a fundamental scientific bottleneck suitable for a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2605.13761)
- [PDF](https://arxiv.org/pdf/2605.13761)

