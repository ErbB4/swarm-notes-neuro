---
# CSL-compatible fields
title: "Context-Aware Hospitalization Forecasting Evaluations for Decision Support using LLMs"
author:
  - literal: "Rhea Makkuni"
  - literal: "Ananya Joshi"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.23949"

# Custom fields
paper_id: "2604.23949"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "llm-applications"
  - "healthcare-analytics"
  - "hybrid-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "hybridarx"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:03:02Z"
created_at: "2026-04-30T06:03:02Z"
---

# Context-Aware Hospitalization Forecasting Evaluations for Decision Support using LLMs

**Authors**: Rhea Makkuni, Ananya Joshi
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.23949](https://arxiv.org/abs/2604.23949)

## Summary

This paper investigates the utility of Large Language Models (LLMs) for hospitalization forecasting during healthcare disruptions by comparing three distinct approaches across 60 U.S. counties. The authors propose HybridARX, a hybrid pipeline that leverages LLM-derived contextual signals to augment structured time-series models. Results indicate that while direct LLM forecasting can be unstable, the HybridARX approach provides superior stability and calibration, particularly under non-stationary conditions, when evaluated using metrics beyond traditional error minimization.

## Key Contributions

- Introduces HybridARX, a context-augmented hybrid pipeline that integrates LLM-derived signals into structured time-series models for hospitalization forecasting.
- Demonstrates that embedding LLMs within structured hybrid models yields more stable and better-calibrated forecasts than direct LLM forecasting or classical ARX models in non-stationary healthcare contexts.
- Evaluates forecasting performance using decision-relevant metrics, specifically bias and lead-lag alignment, across 60 counties with varying hospitalization intensities.

## Open Questions & Future Work

- [[identifying-predictive-exogenous-signals-for-healthcare]]

## Key Concepts

- [[hybridarx]]: A hybrid time-series forecasting pipeline that augments structured models (such as ARX) with contextual signals derived from Large Language Models.

## Archivist Review

I approved the HybridARX framework as a representative pattern for integrating generative model outputs into structured forecasting pipelines. I also approved an open question regarding the identification of predictive exogenous signals in healthcare forecasting to address the broader challenge of distinguishing informative context from noise. Other candidates were rejected for being generic or standard practices in the time-series literature.

### Approved Concepts
- HybridARX: The hybrid approach of grounding LLM-derived context into structured models is a robust paradigm for mitigating the instability of pure LLM forecasting in non-stationary time-series environments.

### Approved Open Questions
- Identifying Predictive Exogenous Signals: Improving forecasting reliability in healthcare requires distinguishing truly predictive context from noise; otherwise, models risk poor generalization and unstable decision support during critical events.

### Rejected Candidates
- [concept] Direct LLM-based forecasting (`llm-based-forecasting`) - generic: Too generic; represents a broad category of application rather than a specific architectural or methodological contribution.
- [concept] Decision-relevant evaluation metrics (`decision-relevant-metrics`) - not_novel: Metrics like bias and lead-lag alignment are standard in time-series analysis and forecasting; they do not require a new conceptual note.

## Links

- [Abstract](https://arxiv.org/abs/2604.23949)
- [PDF](https://arxiv.org/pdf/2604.23949)

