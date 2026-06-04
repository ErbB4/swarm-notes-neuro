---
# CSL-compatible fields
title: "E4GEN: Event-level Explainable Extreme-Enhanced Time-series Generation"
author:
  - literal: "Lin Jiang"
  - literal: "Dahai Yu"
  - literal: "Ximiao Li"
  - literal: "Guang Wang"
issued:
  date-parts:
    - [2026, 6, 1]
url: "https://arxiv.org/abs/2606.01634"

# Custom fields
paper_id: "2606.01634"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "generative-modeling"
  - "diffusion-models"
  - "explainable-ai"
architectures:
  []
datasets:
  []
concept_slugs:
  - "e4gen-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-04T06:34:17Z"
created_at: "2026-06-04T06:34:17Z"
---

# E4GEN: Event-level Explainable Extreme-Enhanced Time-series Generation

**Authors**: Lin Jiang, Dahai Yu, Ximiao Li, Guang Wang
**Date**: 2026-06-01
**Paper ID**: [openalex:2606.01634](https://arxiv.org/abs/2606.01634)

## Summary

E4GEN is an explainable diffusion framework designed to address the poor performance of generative models in capturing rare extreme events within time-series data. The model utilizes a three-component architecture—E-Activator, E-Predictor, and E-Control—to systematically determine when, what, and how to inject extreme events during the denoising process. Unlike standard methods, it leverages self-driven semantic prediction and data-conditioned training to infer control signals even in the absence of explicit training labels. Evaluation across six datasets demonstrates that E4GEN significantly improves both overall fidelity and the accuracy of extreme-value generation compared to state-of-the-art baselines.

## Key Contributions

- Proposes E4GEN, a diffusion-based framework that enables explicit, explainable control over extreme event generation in time-series.
- Introduces a modular architecture comprising E-Activator for adaptive activation, E-Predictor for semantic control signal derivation, and E-Control for targeted signal injection.
- Demonstrates significant performance gains over state-of-the-art generative models across six datasets and 17 metrics, particularly in extreme-event fidelity and downstream utility.

## Key Concepts

- [[e4gen-framework]]: An explainable diffusion framework designed to control and generate extreme events in time-series data while maintaining overall distributional fidelity.

## Archivist Review

I approved the E4GEN framework as it presents a novel, modular approach for injecting control signals into diffusion models to improve extreme event generation, a persistent challenge in time-series synthesis. I rejected the individual sub-components (E-Activator, E-Predictor, E-Control) as they are tightly coupled to the E4GEN architecture and do not represent standalone paradigms at this stage. No open questions or datasets were approved as none met the strict criteria for universality or novelty.

### Approved Concepts
- E4GEN Framework: Central proposed framework for controlled, extreme-event aware time-series generation.

## Links

- [Abstract](https://arxiv.org/abs/2606.01634)
- [PDF](https://arxiv.org/pdf/2606.01634)

