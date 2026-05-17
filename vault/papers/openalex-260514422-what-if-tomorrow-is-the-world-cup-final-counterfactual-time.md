---
# CSL-compatible fields
title: "What if Tomorrow is the World Cup Final? Counterfactual Time Series Forecasting with Textual Conditions"
author:
  - literal: "Shuqi Gu"
  - literal: "Yongxiang Zhao"
  - literal: "Baoyu Jing"
  - literal: "Kan Ren"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14422"

# Custom fields
paper_id: "2605.14422"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "counterfactual-reasoning"
  - "text-conditional-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "text-attribution-mechanism"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:07:04Z"
created_at: "2026-05-17T06:07:04Z"
---

# What if Tomorrow is the World Cup Final? Counterfactual Time Series Forecasting with Textual Conditions

**Authors**: Shuqi Gu, Yongxiang Zhao, Baoyu Jing, Kan Ren
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14422](https://arxiv.org/abs/2605.14422)

## Summary

This paper introduces counterfactual time series forecasting, a new task that models how future events described in text influence time series trajectories. To handle the complexity of linguistic conditions, the authors propose a text-attribution mechanism that explicitly differentiates between mutable factors (those influenced by the event) and immutable ones. The method includes a robust evaluation framework that operates without ground truth data, enabling assessment in purely counterfactual scenarios. Experimental results demonstrate improved predictive accuracy and adaptability compared to methods restricted to structured data.

## Key Contributions

- Defines the task of counterfactual time series forecasting with textual conditions for flexible, condition-aware prediction.
- Introduces a comprehensive evaluation framework for both factual and counterfactual settings, even without ground-truth sequences.
- Develops a text-attribution mechanism that isolates mutable from immutable factors to enhance performance under stochastic textual influences.

## Open Questions & Future Work

- [[evaluation-of-counterfactual-forecasting]]

## Key Concepts

- [[text-attribution-mechanism]]: A mechanism for counterfactual time series forecasting that separates mutable from immutable factors within textual conditions to improve predictive accuracy.

## Archivist Review

I approved the text-attribution mechanism because it provides a reusable, model-agnostic strategy for disentangling causal factors from textual prompts in forecasting. I also approved the open question regarding counterfactual evaluation, as it addresses a fundamental, well-defined bottleneck in the field of time series analysis that persists when factual ground truth is unavailable. Other concepts were rejected as either synonymous with general counterfactual reasoning or too specific to this implementation.

### Approved Concepts
- Text-attribution mechanism: Introduces a core mechanism for grounding counterfactual time series forecasting in natural language while maintaining causal consistency by separating mutable from immutable context.

### Approved Open Questions
- Evaluating Counterfactual Forecasting without Ground Truth: Lack of ground truth is a fundamental bottleneck in counterfactual time series forecasting. Improving evaluation methodologies is essential for establishing reliable benchmarking and model validation in scenarios where true outcomes cannot be realized.

## Links

- [Abstract](https://arxiv.org/abs/2605.14422)
- [PDF](https://arxiv.org/pdf/2605.14422)

