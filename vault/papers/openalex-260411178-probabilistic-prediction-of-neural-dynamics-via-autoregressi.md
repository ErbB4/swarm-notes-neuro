---
# CSL-compatible fields
title: "Probabilistic Prediction of Neural Dynamics via Autoregressive Flow Matching"
author:
  - literal: "Nicole Rogalla"
  - literal: "Yuzhen Qin"
  - literal: "Mario Senden"
  - literal: "Ahmed El-Gazzar"
  - literal: "Marcel van Gerven"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11178"

# Custom fields
paper_id: "2604.11178"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "generative-modeling"
  - "fMRI"
architectures:
  []
datasets:
  []
concept_slugs:
  - "autoregressive-flow-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:51Z"
created_at: "2026-04-16T05:46:51Z"
---

# Probabilistic Prediction of Neural Dynamics via Autoregressive Flow Matching

**Authors**: Nicole Rogalla, Yuzhen Qin, Mario Senden, Ahmed El-Gazzar, Marcel van Gerven
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11178](https://arxiv.org/abs/2604.11178)

## Summary

This paper proposes an Autoregressive Flow Matching (AFM) framework for the probabilistic forecasting of neural dynamics, specifically predicting BOLD fMRI responses. By learning the conditional distribution of future states based on recent neural history and multimodal sensory input, the model captures the temporal evolution of brain activity more effectively than standard GLMs or non-autoregressive approaches. Evaluation on the Algonauts 2025 dataset demonstrates that incorporating autoregressive structure leads to consistent improvements, particularly for short-horizon predictions, highlighting the utility of flow-based generative models for neurotechnology.

## Key Contributions

- Introduces Autoregressive Flow Matching (AFM) to model temporally evolving neural dynamics based on past activity and sensory input.
- AFM achieves superior predictive performance over non-autoregressive flow matching and GLM baselines on fMRI BOLD activity forecasting.
- Demonstrates that historical BOLD dynamics are the primary driver of performance in neural activity forecasting tasks.

## Key Concepts

- [[autoregressive-flow-matching]]: A generative modeling framework that combines flow matching with autoregressive conditioning to learn the conditional distribution of future states in time-evolving systems.

## Archivist Review

I approved the concept 'Autoregressive Flow Matching' as it represents a significant methodological integration of flow-based generative modeling with autoregressive temporal dynamics, which is highly relevant to forecasting. I rejected the Algonauts 2025 dataset because it is a time-bound competition benchmark rather than a fundamental long-term research asset. No open questions were proposed, and none were identified that met the criteria for a permanent vault note.

### Approved Concepts
- Autoregressive Flow Matching: Core methodology proposed for temporal generative modeling of neural data, extending transport-based generative models to autoregressive settings.

### Rejected Candidates
- [dataset] Algonauts project 2025 challenge dataset (`algonauts-project-2025-challenge-dataset`) - low_impact: Standard competition benchmarks are typically not added unless they become foundational domain standards.

## Links

- [Abstract](https://arxiv.org/abs/2604.11178)
- [PDF](https://arxiv.org/pdf/2604.11178)

