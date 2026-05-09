---
# CSL-compatible fields
title: "Driver-WM: A Driver-Centric Traffic-Conditioned Latent World Model for In-Cabin Dynamics Rollout"
author:
  - literal: "Haozhuang Chi"
  - literal: "Daosheng Qiu"
  - literal: "Hao Su"
  - literal: "Haochen Liu"
  - literal: "Zirui Li"
  - literal: "Haoruo Zhang"
  - literal: "Chen Lv"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05092"

# Custom fields
paper_id: "2605.05092"
paper_source: "openalex"
domain: "nlp"
tags:
  - "nlp"
  - "time-series-forecasting"
  - "latent-space-modeling"
  - "causal-inference"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gated-causal-injection-mechanism"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:57:54Z"
created_at: "2026-05-09T05:57:54Z"
---

# Driver-WM: A Driver-Centric Traffic-Conditioned Latent World Model for In-Cabin Dynamics Rollout

**Authors**: Haozhuang Chi, Daosheng Qiu, Hao Su, Haochen Liu, Zirui Li, Haoruo Zhang, Chen Lv
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.05092](https://arxiv.org/abs/2605.05092)

## Summary

Driver-WM is a latent world model that forecasts driver-centric in-cabin dynamics by causally conditioning on external traffic conditions. The model employs a dual-stream architecture that processes external traffic and driver states independently, using a gated causal injection mechanism to maintain temporal dependencies. This approach enables both long-horizon geometric forecasting of driver maneuvers and semantic recognition of behavioral states, facilitating controlled test-time interventions for safer L2/L3 automation.

## Key Contributions

- Introduces Driver-WM, a latent world model specifically designed for forecasting in-cabin human dynamics conditioned on external traffic context.
- Implements a dual-stream architecture with gated causal injection to enforce temporal causality between external environmental and internal driver latent representations.
- Demonstrates superior long-horizon geometric forecasting for high-motion maneuvers and improved semantic alignment on a multi-task assistive driving benchmark.

## Open Questions & Future Work

- [[anticipating-reactive-driver-dynamics]]

## Key Concepts

- [[gated-causal-injection-mechanism]]: A mechanism that uses learned vector gates to modulate external contextual perturbations in a latent world model while enforcing temporal causality.

## Archivist Review

I approved the gated causal injection mechanism as a reusable structural concept for directional conditioning in latent world models. I also approved a research question focused on the bottleneck of human-centered latent dynamics forecasting in autonomous systems. No datasets were approved as none were clearly named or unique enough for standalone note utility.

### Approved Concepts
- Gated Causal Injection Mechanism: The core contribution for enabling directional coupling between external traffic and internal driver state streams while maintaining causality.

### Approved Open Questions
- Anticipating Reactive Driver Dynamics: This represents a fundamental bottleneck in achieving safe, human-centered L2/L3 automation, as existing systems lack the capability to anticipate driver responses to specific environment triggers, leading to limitations in maneuver planning and safety-critical intervention.

## Links

- [Abstract](https://arxiv.org/abs/2605.05092)
- [PDF](https://arxiv.org/pdf/2605.05092)

