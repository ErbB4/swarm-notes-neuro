---
title: "Multi-stepsize Mixture-of-Experts (Ms-MoE)"
slug: "ms-moe-neural-operator"
type: concept
generated_stub: true
source_papers:
  - "[[openalex-260412794-stable-fine-time-step-long-horizon-turbulence-prediction-wit]]"
processed_at: "2026-04-17T05:47:03Z"
created_at: "2026-04-17T05:47:03Z"
---

# Multi-stepsize Mixture-of-Experts (Ms-MoE)

> *Auto-generated stub. Edit this file to add more details.*

A mixture-of-experts architecture that conditions on temporal stride to maintain stability and accuracy across varying time-steps in forecasting models.


## Why It Matters

Provides a novel mechanism for handling multi-scale temporal dynamics in neural operators, which is a common bottleneck in long-horizon forecasting.

## Evidence

> The model conditions on a requested relative stride and uses a time-step router to activate scale-specific routed experts together with a shared expert.

## Related Papers

- [[openalex-260412794-stable-fine-time-step-long-horizon-turbulence-prediction-wit]]
