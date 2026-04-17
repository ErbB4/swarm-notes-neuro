---
# CSL-compatible fields
title: "Do VLMs Truly \"Read\" Candlesticks? A Multi-Scale Benchmark for Visual Stock Price Forecasting"
author:
  - literal: "Kaiqi Hu"
  - literal: "Linda Xiao"
  - literal: "Shiyue Xu"
  - literal: "Ziyi Tang"
  - literal: "Mingwen Liu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12659"

# Custom fields
paper_id: "2604.12659"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:45:52Z"
created_at: "2026-04-17T05:45:52Z"
---

# Do VLMs Truly "Read" Candlesticks? A Multi-Scale Benchmark for Visual Stock Price Forecasting

**Authors**: Kaiqi Hu, Linda Xiao, Shiyue Xu, Ziyi Tang, Mingwen Liu
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12659](https://arxiv.org/abs/2604.12659)

## Summary

This paper investigates the true visual reasoning capabilities of Vision-Language Models (VLMs) in the context of stock price forecasting using candlestick charts. By constructing a multi-scale dataset, the authors challenge the assumption that VLMs effectively process temporal visual market dynamics. The study reveals that while VLMs perform acceptably in strong trend scenarios, they fail in complex market conditions and lack precise temporal sensitivity, necessitating a more rigorous approach to evaluating visual financial reasoning.

## Key Contributions

- Introduces a multi-scale candlestick chart dataset to evaluate the integration of short-term and long-term visual market dynamics in VLMs.
- Develops a standardized evaluation framework combining confusion-matrix diagnostics and information coefficient (IC) metrics.
- Demonstrates that current VLMs struggle with non-trending market conditions and show significant prediction biases regarding specified forecast horizons.

## Open Questions & Future Work

- [[vlm-financial-concept-comprehension]]

## Archivist Review

The paper provides a timely evaluation of VLM capabilities in financial time series forecasting. I have approved one open question regarding financial concept comprehension, as this addresses a fundamental bottleneck in verifying whether models are performing genuine technical analysis rather than simply pattern matching. I rejected the fine-tuning question as it is a standard empirical iteration rather than a structural research question. No concepts were approved as the metrics and datasets mentioned are standardized components rather than reusable conceptual frameworks for the broader time-series community.

### Approved Open Questions
- Evaluating VLM Financial Conceptual Understanding: Moving beyond aggregate performance metrics is essential to verify if models are truly performing technical analysis based on established financial theory or simply exploiting superficial statistical correlations.

### Rejected Candidates
- [open_question] Necessity of Task-Specific Fine-tuning (`vlm-candlestick-finetuning-necessity`) - not_novel: The question of whether fine-tuning improves performance is a standard empirical question for any model architecture, not a fundamental unresolved bottleneck in the domain of time series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.12659)
- [PDF](https://arxiv.org/pdf/2604.12659)

