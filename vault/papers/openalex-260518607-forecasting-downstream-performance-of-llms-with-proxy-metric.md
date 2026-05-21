---
# CSL-compatible fields
title: "Forecasting Downstream Performance of LLMs With Proxy Metrics"
author:
  - literal: "Arkil Patel"
  - literal: "Siva Reddy"
  - literal: "Marius Mosbach"
  - literal: "Dzmitry Bahdanau"
issued:
  date-parts:
    - [2026, 5, 18]
url: "https://arxiv.org/abs/2605.18607"

# Custom fields
paper_id: "2605.18607"
paper_source: "openalex"
domain: "nlp"
tags:
  - "llm-training-efficiency"
  - "performance-forecasting"
  - "model-selection"
  - "data-curation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "expert-trajectory-proxy-metrics"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-21T06:26:41Z"
created_at: "2026-05-21T06:26:41Z"
---

# Forecasting Downstream Performance of LLMs With Proxy Metrics

**Authors**: Arkil Patel, Siva Reddy, Marius Mosbach, Dzmitry Bahdanau
**Date**: 2026-05-18
**Paper ID**: [openalex:2605.18607](https://arxiv.org/abs/2605.18607)

## Summary

This paper addresses the challenge of accurately forecasting downstream language model performance without expensive direct evaluation. The authors propose proxy metrics based on token-level statistics, such as entropy and token rank, computed over expert-written solutions rather than relying on standard cross-entropy loss. These proxies consistently outperform traditional compute-based and loss-based baselines in model selection, data curation, and training-time extrapolation scenarios. The results demonstrate that leveraging expert-curated data provides a robust, low-cost signal for assessing LLM capabilities across the development life cycle.

## Key Contributions

- Introduces proxy metrics derived from token-level statistics on expert-written solutions to forecast downstream LLM performance.
- Achieves mean Spearman Rho of 0.81 for cross-family model selection, significantly outperforming cross-entropy loss (0.36).
- Demonstrates pretraining data selection at 10,000x lower compute cost than direct evaluation, improving the Pareto frontier.
- Enables reliable training-time accuracy extrapolation across 18x compute horizons with reduced error compared to baseline methods.

## Key Concepts

- [[expert-trajectory-proxy-metrics]]: A forecasting framework that estimates downstream LLM capabilities by aggregating token-level statistics from the model's output distribution on expert-curated solution sequences.

## Archivist Review

I have approved the core methodological concept of using expert-written trajectories as a signal for LLM forecasting, as it provides a superior alternative to cross-entropy loss for downstream capability estimation. I have rejected the generic tags and task categories provided in the original input, as they do not meet the criteria for standalone technical contributions in the vault.

### Approved Concepts
- Expert-Trajectory-Proxy-Metrics: Provides a computationally efficient and more aligned alternative to cross-entropy loss for forecasting downstream LLM performance.

### Rejected Candidates
- [concept] llm-training-efficiency (`llm-training-efficiency`) - generic: This is a generic field label rather than a specific algorithmic contribution.
- [concept] performance-forecasting (`performance-forecasting`) - generic: This is a high-level task category rather than a specific methodology.
- [concept] model-selection (`model-selection`) - generic: A standard model engineering practice, not a unique contribution.
- [concept] data-curation (`data-curation`) - generic: A common machine learning pipeline phase.

## Links

- [Abstract](https://arxiv.org/abs/2605.18607)
- [PDF](https://arxiv.org/pdf/2605.18607)

