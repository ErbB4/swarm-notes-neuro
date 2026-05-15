---
# CSL-compatible fields
title: "Agent-Based Post-Hoc Correction of Agricultural Yield Forecasts"
author:
  - literal: "Matthew Beddows"
  - literal: "Aiden Durrant"
  - literal: "Georgios Leontidis"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12375"

# Custom fields
paper_id: "2605.12375"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "llm-agents"
  - "agriculture"
architectures:
  []
datasets:
  - "usda-corn-harvest-dataset"
concept_slugs:
  - "agentic-time-series-forecasting"
dataset_slugs:
  - "usda-corn-harvest-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:14:49Z"
created_at: "2026-05-15T06:14:49Z"
---

# Agent-Based Post-Hoc Correction of Agricultural Yield Forecasts

**Authors**: Matthew Beddows, Aiden Durrant, Georgios Leontidis
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12375](https://arxiv.org/abs/2605.12375)

## Summary

This paper addresses the challenge of accurate crop yield forecasting in data-constrained agricultural environments. The authors propose an LLM agent framework that performs post-hoc correction of existing model predictions by utilizing domain-specific tools for phase detection, bias learning, and range validation. Empirical results across proprietary strawberry and public USDA corn datasets demonstrate significant reductions in error metrics compared to standalone XGBoost, Random Forest, and Moirai2 baselines. The study highlights the effectiveness of specialized LLM refinement and notes significant sensitivity to the choice of the agent's underlying model.

## Key Contributions

- Introduces a structured LLM agent framework that improves agricultural yield forecasts by post-hoc correction of existing predictive models.
- Demonstrates consistent performance improvements over XGBoost, Moirai2, and Random Forest baselines, reducing MAE by up to 28% and MASE by up to 66%.
- Provides empirical evidence that LLM agent performance for time series refinement is sensitive to the underlying model architecture (e.g., Llama 3.1 8B vs LLaVA 13B).

## Open Questions & Future Work

- [[generalizing-agentic-correction-to-irregular-cycles]]

## Key Concepts

- [[agentic-time-series-forecasting]]: A structured LLM agent framework designed to perform post-hoc error correction and refinement of time series forecasts using domain-specific tools.

## Archivist Review

The proposed agentic framework is a novel, reusable paradigm for post-hoc time series correction. I approved the concept and a refined version of the open question regarding the generalizability of these techniques to irregular temporal patterns. The USDA corn dataset was included as it is a standard, recognizable, and reusable public benchmark in agricultural forecasting.

### Approved Concepts
- Agentic Time Series Forecasting: Represents a shift from end-to-end learning to a tool-augmented reasoning paradigm for time series correction, decoupling the forecast model from the validation logic.

### Approved Open Questions
- Generalizing agentic correction to irregular cycles: Expanding agentic correction to diverse agricultural production systems is critical for practical scalability beyond standard seasonal monocultures.

### Rejected Candidates
- [open_question] Adapting agents to non-seasonal crops (`adapting-agentic-correction-to-non-seasonal-crops`) - other: Renamed for better conciseness and conceptual alignment with vault standards.

## Datasets

- [[usda-corn-harvest-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.12375)
- [PDF](https://arxiv.org/pdf/2605.12375)

