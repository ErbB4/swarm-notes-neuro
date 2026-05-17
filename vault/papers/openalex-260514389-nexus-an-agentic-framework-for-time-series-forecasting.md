---
# CSL-compatible fields
title: "Nexus : An Agentic Framework for Time Series Forecasting"
author:
  - literal: "Sarkar Snigdha Sarathi Das"
  - literal: "Palash Goyal"
  - literal: "Mihir Parmar"
  - literal: "Nanyun Peng"
  - literal: "Vishy Tirumalashetty"
  - literal: "Chunliang Li"
  - literal: "Rui Zhang"
  - literal: "Jinsung Yoon"
  - literal: "Tomas Pfister"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14389"

# Custom fields
paper_id: "2605.14389"
paper_source: "openalex"
domain: "nlp"
tags:
  - "nlp"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "agentic-time-series-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:06:57Z"
created_at: "2026-05-17T06:06:57Z"
---

# Nexus : An Agentic Framework for Time Series Forecasting

**Authors**: Sarkar Snigdha Sarathi Das, Palash Goyal, Mihir Parmar, Nanyun Peng, Vishy Tirumalashetty, Chunliang Li, Rui Zhang, Jinsung Yoon, Tomas Pfister
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14389](https://arxiv.org/abs/2605.14389)

## Summary

Nexus is a multi-agent forecasting framework that addresses the limitation of current TSFMs and LLMs in integrating unstructured context with numerical data. By decomposing the forecasting process into macro-level and micro-level temporal isolation and contextual integration stages, the framework enables superior adaptation to event-driven volatility. The approach proves that LLMs can achieve high-performance forecasting when given an structured, agentic reasoning pipeline, and provides explicit reasoning traces for all predictions.

## Key Contributions

- Introduces Nexus, a multi-agent framework that decomposes time series forecasting into distinct stages for isolating temporal fluctuations and integrating contextual information.
- Demonstrates that LLMs exhibit strong intrinsic forecasting capabilities when numerical and contextual reasoning processes are structurally organized.
- Outperforms state-of-the-art Time Series Foundation Models (TSFMs) and LLM baselines on real estate and stock market data, even when datasets strictly succeed LLM knowledge cutoffs.

## Open Questions & Future Work

- [[scalability-of-agentic-forecasting]]

## Key Concepts

- [[agentic-time-series-forecasting]]: A multi-agent framework that decomposes forecasting into specialized stages for integrating numerical and contextual data through reasoning.

## Archivist Review

I approved the concept of Agentic Time Series Forecasting as it defines a novel paradigm shift for integrating unstructured data into temporal reasoning, and an open question regarding the scalability of such approaches due to their high computational overhead. Other candidates were rejected to maintain the required scarcity of the vault and to avoid duplicating existing nomenclature. All selections focus on long-term research bottlenecks in combining foundation model reasoning with time series tasks.

### Approved Concepts
- Agentic Time Series Forecasting: It shifts the paradigm of time series forecasting from pure sequence modeling to a multi-stage agentic reasoning problem, allowing the integration of unstructured context.

### Approved Open Questions
- Scalability of Agentic Forecasting: This is a fundamental challenge for the adoption of agentic forecasting in production environments where cost-efficiency and robust statistical validation are prerequisites.

### Rejected Candidates
- [open_question] Scalability of Agentic Forecasting (`scalability-and-cost-of-agentic-forecasting`) - other: The candidate was renamed for conciseness to better fit vault standards while maintaining the core research question.

## Links

- [Abstract](https://arxiv.org/abs/2605.14389)
- [PDF](https://arxiv.org/pdf/2605.14389)

