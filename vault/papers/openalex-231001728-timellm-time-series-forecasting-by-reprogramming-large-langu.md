---
# CSL-compatible fields
title: "TimeLLM: Time Series Forecasting by Reprogramming Large Language Models"
author:
  - literal: "Ming Jin"
  - literal: "Shiyu Wang"
  - literal: "Lintao Ma"
  - literal: "Zhixuan Chu"
  - literal: "James Y. Zhang"
  - literal: "Xiaoming Shi"
  - literal: "Pin‐Yu Chen"
  - literal: "Yuxuan Liang"
  - literal: "Yuan-Fang Li"
  - literal: "Shirui Pan"
  - literal: "Qingsong Wen"
issued:
  date-parts:
    - [2026, 5, 18]
url: "https://arxiv.org/abs/2310.01728"

# Custom fields
paper_id: "2310.01728"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-augmented-generation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "time-llm"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-21T06:24:30Z"
created_at: "2026-05-21T06:24:30Z"
---

# TimeLLM: Time Series Forecasting by Reprogramming Large Language Models

**Authors**: Ming Jin, Shiyu Wang, Lintao Ma, Zhixuan Chu, James Y. Zhang, Xiaoming Shi, Pin‐Yu Chen, Yuxuan Liang, Yuan-Fang Li, Shirui Pan, Qingsong Wen
**Date**: 2026-05-18
**Paper ID**: [openalex:2310.01728](https://arxiv.org/abs/2310.01728)

## Summary

Time-LLM is a novel framework that bridges the gap between numerical time series data and linguistic models by reprogramming frozen large language models. It employs a modality alignment strategy to transform time series input patches into text-like prototypes, which are then combined with prompt prefixes to leverage the LLM's inherent reasoning capabilities. This multimodal approach effectively allows language models to function as powerful forecasting engines without the need for intensive re-training. Extensive experiments demonstrate that Time-LLM consistently outperforms specialized forecasting baselines across various datasets.

## Key Contributions

- Introduces Time-LLM, a model reprogramming framework that repurposes frozen LLMs for time series forecasting.
- Develops a modality alignment technique that embeds raw time series data into text prototypes.
- Proposes Prompt-as-Prefix (PaP) to augment contextual information and enhance LLM reasoning for time series signals.
- Achieves state-of-the-art performance against specialized baseline models across multiple time series forecasting benchmarks.

## Key Concepts

- [[time-llm]]: A model reprogramming framework that adapts frozen large language models for time series forecasting tasks by mapping numerical signals to linguistic prototypes.

## Archivist Review

I approved Time-LLM as a central concept representing the paradigm of reprogramming LLMs for time series forecasting. I rejected the prompt-as-prefix (PaP) mechanism as it is a sub-component of the broader Time-LLM framework. No datasets or open questions were proposed, so none were approved.

### Approved Concepts
- Time-LLM: It introduces a model reprogramming framework to leverage frozen LLM backbones for time series forecasting without fine-tuning, shifting the paradigm of time series modeling.

### Rejected Candidates
- [concept] Prompt-as-Prefix (`prompt-as-prefix`) - subcomponent_of_broader_mechanism: This is a specific sub-component technique of the broader Time-LLM framework and does not warrant a separate note.

## Links

- [Abstract](https://arxiv.org/abs/2310.01728)
- [PDF](https://arxiv.org/pdf/2310.01728)

