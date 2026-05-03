---
# CSL-compatible fields
title: "CastFlow: Learning Role-Specialized Agentic Workflows for Time Series Forecasting"
author:
  - literal: "潘柏凱"
  - literal: "Mingyue Cheng"
  - literal: "Zhiding Liu"
  - literal: "Shuo Yu"
  - literal: "Xiaoyu Tao"
  - literal: "Yuchong Wu"
  - literal: "Qi Liu"
  - literal: "Defu Lian"
  - literal: "Enhong Chen"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27840"

# Custom fields
paper_id: "2604.27840"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-question-answering-tsqa"
architectures:
  []
datasets:
  []
concept_slugs:
  - "agentic-time-series-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:20Z"
created_at: "2026-05-03T06:02:20Z"
---

# CastFlow: Learning Role-Specialized Agentic Workflows for Time Series Forecasting

**Authors**: 潘柏凱, Mingyue Cheng, Zhiding Liu, Shuo Yu, Xiaoyu Tao, Yuchong Wu, Qi Liu, Defu Lian, Enhong Chen
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27840](https://arxiv.org/abs/2604.27840)

## Summary

CastFlow is an agentic framework that replaces the traditional one-shot LLM forecasting paradigm with a dynamic, multi-stage workflow involving planning, multi-view feature acquisition, and iterative refinement. By combining a frozen general-purpose LLM for reasoning with a fine-tuned, role-specialized LLM for numerical tasks, the framework leverages ensemble baselines to improve accuracy. The approach is optimized via a novel two-stage training process, achieving superior performance on diverse time series benchmarks compared to existing static models.

## Key Contributions

- Introduced CastFlow, an agentic forecasting framework that incorporates multi-view temporal pattern extraction and iterative forecast refinement.
- Developed a role-specialized architecture separating general-purpose reasoning (frozen LLM) from domain-specific numerical forecasting (fine-tuned LLM).
- Proposed a two-stage training paradigm using supervised fine-tuning and reinforcement learning with verifiable rewards (RLVR) to optimize agentic workflows.

## Open Questions & Future Work

- [[joint-reasoning-numerical-accuracy-bottleneck]]

## Key Concepts

- [[agentic-time-series-forecasting]]: A paradigm for time series forecasting where LLMs iteratively plan, extract multi-view temporal features, and refine predictions through reflective workflows.

## Archivist Review

The paper introduces a shift towards agentic, multi-stage workflows in LLM-based time series forecasting. I have generalized the framework name 'CastFlow' into a more reusable concept note for 'Agentic Time Series Forecasting'. The open question regarding the trade-off between reasoning and numerical accuracy in such agents addresses a significant, non-boilerplate bottleneck.

### Approved Concepts
- Agentic Time Series Forecasting: It shifts the LLM forecasting paradigm from static, one-shot inference to iterative, multi-stage agentic workflows, enabling reasoning and reflection.

### Approved Open Questions
- Joint Reasoning-Numerical Accuracy Bottleneck: This captures the fundamental bottleneck in current agentic LLM-forecasting frameworks, specifically regarding the interaction between frozen reasoning models and fine-tuned numerical predictors.

### Rejected Candidates
- [concept] CastFlow (`castflow`) - paper_local: This is a specific framework name, better categorized under the more general Agentic Time Series Forecasting concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.27840)
- [PDF](https://arxiv.org/pdf/2604.27840)

