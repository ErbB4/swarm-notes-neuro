---
# CSL-compatible fields
title: "Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs"
author:
  - literal: "Kevin Murphy"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18576"

# Custom fields
paper_id: "2604.18576"
paper_source: "openalex"
domain: "nlp"
tags:
  - "forecasting"
  - "llm-agents"
  - "bayesian-inference"
  - "calibration"
architectures:
  []
datasets:
  - "forecastbench"
concept_slugs:
  - "bayesian-linguistic-belief-state"
dataset_slugs:
  - "forecastbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:47:33Z"
created_at: "2026-04-23T05:47:33Z"
---

# Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs

**Authors**: Kevin Murphy
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18576](https://arxiv.org/abs/2604.18576)

## Summary

BLF (Bayesian Linguistic Forecaster) is an agentic framework for binary forecasting that improves decision-making by replacing monolithic context window accumulation with a structured Bayesian belief state. This state effectively fuses numerical probability estimates with iterative natural-language evidence summaries generated via tool-use. Furthermore, the system incorporates hierarchical shrinkage aggregation and calibration techniques to handle uncertainty and base-rate skew. Evaluations on 400 backtesting questions from the ForecastBench benchmark demonstrate that BLF outperforms leading models while maintaining a rigorous, low-leakage testing protocol.

## Key Contributions

- Introduced the BLF agentic forecasting system, achieving state-of-the-art performance on the ForecastBench benchmark.
- Developed the Bayesian linguistic belief state, a memory-efficient semi-structured representation for LLM iterative reasoning.
- Proposed hierarchical multi-trial logit-space shrinkage and hierarchical Platt scaling for robust probability calibration.

## Open Questions & Future Work

- [[agentic-forecasting-model-transferability]]

## Key Concepts

- [[bayesian-linguistic-belief-state]]: A semi-structured state representation that combines numerical probabilities with natural-language evidence summaries, maintained through iterative updates.

## Archivist Review

The 'Bayesian Linguistic Belief State' is approved as a significant contribution to agentic memory management in long-horizon forecasting. I renamed the open question to be more descriptive of the scientific uncertainty regarding architectural transferability and rejected the tool-specific question as it reflects common implementation refinement rather than a core research bottleneck. The ForecastBench dataset is approved as a primary evaluation tool for this class of model.

### Approved Concepts
- Bayesian Linguistic Belief State: It introduces a novel way to manage agentic memory and reasoning by explicitly decoupling belief representation from raw context window growth, a critical bottleneck in long-horizon forecasting.

### Approved Open Questions
- Agentic Forecasting Model Transferability: Understanding model-agnosticism is critical for determining the scalability and robustness of the agentic forecasting framework across different computational environments.

### Rejected Candidates
- [open_question] Enhancing Domain-Specific Forecasting Tools (`domain-specific-tool-development-forecasting`) - low_impact: This is essentially a request for better tools/data features rather than a fundamental scientific research question about the forecasting mechanism itself.

## Datasets

- [[forecastbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.18576)
- [PDF](https://arxiv.org/pdf/2604.18576)

