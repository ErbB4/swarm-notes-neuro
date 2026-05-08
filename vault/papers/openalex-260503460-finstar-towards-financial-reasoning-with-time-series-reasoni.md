---
# CSL-compatible fields
title: "FinSTaR: Towards Financial Reasoning with Time Series Reasoning Models"
author:
  - literal: "Seunghan Lee"
  - literal: "Jun Seo"
  - literal: "Jaehoon Lee"
  - literal: "Sungdong Yoo"
  - literal: "Minjae Kim"
  - literal: "Tae Yoon Lim"
  - literal: "Dongwan Kang"
  - literal: "Hwanil Choi"
  - literal: "Soonyoung Lee"
  - literal: "Wonbin Ahn"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03460"

# Custom fields
paper_id: "2605.03460"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "fintsr-bench"
concept_slugs:
  - "compute-in-cot"
  - "scenario-aware-cot"
dataset_slugs:
  - "fintsr-bench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-08T05:43:31Z"
created_at: "2026-05-08T05:43:31Z"
---

# FinSTaR: Towards Financial Reasoning with Time Series Reasoning Models

**Authors**: Seunghan Lee, Jun Seo, Jaehoon Lee, Sungdong Yoo, Minjae Kim, Tae Yoon Lim, Dongwan Kang, Hwanil Choi, Soonyoung Lee, Wonbin Ahn
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03460](https://arxiv.org/abs/2605.03460)

## Summary

FinSTaR is a novel framework designed to improve time series reasoning models (TSRMs) specifically for the financial domain. The authors introduce a 2x2 capability taxonomy and a corresponding benchmark, FinTSR-Bench, which evaluate model performance on deterministic assessments and stochastic predictions. To address these distinct challenges, the framework employs Compute-in-CoT for deterministic calculation and Scenario-Aware CoT for handling stochastic uncertainty, significantly outperforming existing baselines.

## Key Contributions

- Proposed a 2x2 capability taxonomy for Financial Time Series Reasoning Models (TSRMs) categorizing analysis by entity count and temporal focus (assessment vs. prediction).
- Introduced FinTSR-Bench, a comprehensive benchmark based on S&P stocks that instantiates the proposed 2x2 taxonomy into ten distinct reasoning tasks.
- Developed FinSTaR, a reasoning framework that achieves 78.9% average accuracy on FinTSR-Bench by utilizing task-specific Chain-of-Thought (CoT) strategies.

## Open Questions & Future Work

- [[financial-prediction-ceiling]]

## Key Concepts

- [[compute-in-cot]]: A programmatic chain-of-thought strategy that enables models to derive deterministic financial assessments directly from raw price data.
- [[scenario-aware-cot]]: A reasoning strategy that generates diverse future scenarios to handle uncertainty in stochastic time series forecasting tasks.

## Archivist Review

I have approved the two CoT reasoning strategies as they represent reusable paradigms for bridging programmatic and stochastic reasoning in time series models. FinTSR-Bench is included as a core, well-defined benchmark for the financial domain, and the performance ceiling question is maintained as a fundamental epistemic constraint on financial forecasting research. All candidates were evaluated for their broader applicability to the TimeSeriesSkill context.

### Approved Concepts
- Compute-in-CoT: Provides a programmatic bridge between raw financial time series data and reasoning by grounding deterministic tasks in verifiable computation.
- Scenario-Aware CoT: Addresses the stochastic nature of financial forecasting by forcing the model to deliberate on multiple potential outcomes before producing a final decision.

### Approved Open Questions
- Financial Prediction Performance Ceiling: This is a fundamental limitation that directly impacts the utility of reasoning models in financial decision-making and defines the scope of what models can realistically achieve.

## Datasets

- [[fintsr-bench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.03460)
- [PDF](https://arxiv.org/pdf/2605.03460)

