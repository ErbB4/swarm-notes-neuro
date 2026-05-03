---
# CSL-compatible fields
title: "ABC: Any-Subset Autoregression via Non-Markovian Diffusion Bridges in Continuous Time and Space"
author:
  - literal: "Gabe Guo"
  - literal: "Thanawat Sornwanee"
  - literal: "Lutong Hao"
  - literal: "Elon Litman"
  - literal: "Stefano Ermon"
  - literal: "Jose Blanchet"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27443"

# Custom fields
paper_id: "2604.27443"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "generative-modeling"
  - "diffusion-models"
  - "stochastic-differential-equations"
architectures:
  []
datasets:
  []
concept_slugs:
  - "any-subset-autoregression"
  - "non-markovian-diffusion-bridge"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:03:22Z"
created_at: "2026-05-03T06:03:22Z"
---

# ABC: Any-Subset Autoregression via Non-Markovian Diffusion Bridges in Continuous Time and Space

**Authors**: Gabe Guo, Thanawat Sornwanee, Lutong Hao, Elon Litman, Stefano Ermon, Jose Blanchet
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27443](https://arxiv.org/abs/2604.27443)

## Summary

ABC is a novel framework for generating continuous-time, continuous-space stochastic processes conditioned on arbitrary subsets of observations. Unlike standard diffusion models that start from pure noise, ABC models the process through a single continual SDE where intermediate states track physical time and process states. This approach allows for path-dependent conditioning on irregularly sampled timesteps and future observations, while ensuring physically plausible dynamics by scaling noise injection appropriately. Experiments demonstrate significant improvements in video generation and weather forecasting tasks compared to existing diffusion-based baselines.

## Key Contributions

- Introduces ABC, a continuous-time and continuous-space diffusion bridge framework for conditional stochastic process generation.
- Enables conditioning on arbitrary subsets of temporal states by modeling processes via a single continual SDE using path-space measure changes.
- Achieves physically plausible dynamics by scaling noise injection with physical time elapsed and utilizing state-adjacent generation instead of uninformative noise.

## Open Questions & Future Work

- [[non-markovian-history-compression-bottleneck]]

## Key Concepts

- [[any-subset-autoregression]]: A generative framework that enables conditioning on non-contiguous, irregularly sampled observations by modeling stochastic processes through continual SDEs.
- [[non-markovian-diffusion-bridge]]: A generative diffusion process where transition dynamics are conditioned on past and future observations, relaxing the standard Markovian assumption.

## Archivist Review

I approved 'Any-Subset Autoregression' and 'Non-Markovian Diffusion Bridge' as core conceptual contributions that offer a distinct, reusable paradigm for continuous-time generative modeling. The open question regarding history compression was approved as it targets a specific, substantial bottleneck for this class of models. No datasets were identified as central or distinct enough to warrant a new entry.

### Approved Concepts
- Any-Subset Autoregression: Provides a novel approach to conditional generative modeling by allowing flexible conditioning on arbitrary temporal subsets rather than fixed sequential histories.
- Non-Markovian Diffusion Bridge: Enables modeling long-range temporal dependencies and path-dependent dynamics by conditioning on arbitrary historical/future states within a diffusion framework.

### Approved Open Questions
- Non-Markovian History Compression Bottleneck: Addressing the computational overhead of path-dependent history is critical for the application of non-Markovian generative models to long-range forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.27443)
- [PDF](https://arxiv.org/pdf/2604.27443)

