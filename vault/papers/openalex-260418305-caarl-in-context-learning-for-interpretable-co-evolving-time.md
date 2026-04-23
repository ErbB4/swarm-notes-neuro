---
# CSL-compatible fields
title: "CAARL: In-Context Learning for Interpretable Co-Evolving Time Series Forecasting"
author:
  - literal: "Etienne Tajeuna"
  - literal: "Patrick Owusu"
  - literal: "Armelle Brun"
  - literal: "Shengrui Wang"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18305"

# Custom fields
paper_id: "2604.18305"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "large-language-models"
  - "interpretability"
  - "in-context-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "narrative-serialization-temporal-graphs"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:46:52Z"
created_at: "2026-04-23T05:46:52Z"
---

# CAARL: In-Context Learning for Interpretable Co-Evolving Time Series Forecasting

**Authors**: Etienne Tajeuna, Patrick Owusu, Armelle Brun, Shengrui Wang
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18305](https://arxiv.org/abs/2604.18305)

## Summary

CAARL is an interpretable forecasting framework designed for co-evolving time series by leveraging LLMs through in-context learning. The model decomposes time series into autoregressive segments, builds a temporal dependency graph, and serializes this graph into a narrative reasoning trace. This approach allows the LLM to generate predictions alongside transparent explanations of the underlying contextual dynamics. Empirical results demonstrate that CAARL effectively handles nonstationary dynamics and complex inter-dependencies while providing superior interpretability compared to standard black-box forecasting models.

## Key Contributions

- Introduced CAARL, a novel architecture that serializes temporal dependency graphs of co-evolving time series into narrative input for LLMs to enable contextual forecasting.
- Enabled chain-of-thought interpretability in time series forecasting by linking future predictions to explicit, generated reasoning traces regarding system dynamics.
- Demonstrated superior or competitive performance against state-of-the-art forecasting methods on complex, nonstationary co-evolving time series benchmarks.

## Open Questions & Future Work

- [[interpretable-llm-forecasting-bottleneck-coevolving-systems]]

## Key Concepts

- [[narrative-serialization-temporal-graphs]]: A technique for converting structural temporal dependency information into narrative text inputs for LLMs to support reasoning-based forecasting.

## Archivist Review

I approved the narrative serialization mechanism as a distinct, reusable methodology for LLM-based time series modeling, preferring it over the specific model architecture name CAARL. I also approved the open question regarding the structural interpretability bottleneck in LLM-based forecasting, as it addresses a fundamental challenge for the field. The review followed the strict policy of avoiding model-specific branding in favor of transferable techniques and concepts.

### Approved Concepts
- Narrative Serialization of Temporal Graphs: It provides a generalized mechanism for bridging structural time series representation (graphs) and LLM-based reasoning (natural language prompts).

### Approved Open Questions
- LLM Structural Transparency Bottleneck: This bottleneck is critical for the adoption of LLMs in fields requiring auditability and causal understanding of forecasting outputs.

### Rejected Candidates
- [concept] ContextAware ARLLM (CAARL) (`caarl`) - subcomponent_of_broader_mechanism: The proposed concept is a specific model architecture; I have approved the underlying technique of narrative serialization instead, which is more reusable.

## Links

- [Abstract](https://arxiv.org/abs/2604.18305)
- [PDF](https://arxiv.org/pdf/2604.18305)

