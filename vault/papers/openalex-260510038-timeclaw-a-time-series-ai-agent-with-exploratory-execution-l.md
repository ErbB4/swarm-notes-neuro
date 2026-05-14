---
# CSL-compatible fields
title: "TimeClaw: A Time-Series AI Agent with Exploratory Execution Learning"
author:
  - literal: "Hangchen Liu"
  - literal: "Dongyuan Li"
  - literal: "Renhe Jiang"
  - literal: "Jiewen Deng"
  - literal: "Weiwei Ye"
  - literal: "Yoshihide Sekimoto"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10038"

# Custom fields
paper_id: "2605.10038"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "timeclaw"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:04Z"
created_at: "2026-05-14T06:09:04Z"
---

# TimeClaw: A Time-Series AI Agent with Exploratory Execution Learning

**Authors**: Hangchen Liu, Dongyuan Li, Renhe Jiang, Jiewen Deng, Weiwei Ye, Yoshihide Sekimoto
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10038](https://arxiv.org/abs/2605.10038)

## Summary

TimeClaw is an exploratory execution learning framework designed to improve time-series agentic reasoning by transforming diverse exploratory tool executions into reusable hierarchical experiences. Unlike traditional execution-centric models that risk tool-prior collapse after early success, TimeClaw employs a structured four-stage loop to compare and distill execution performance before reinjecting that knowledge into the inference process. The system remains frozen throughout, preventing the risks associated with online test-time adaptation while significantly enhancing accuracy on complex forecasting and reasoning tasks. Experimental results on 17 finance and weather-related benchmarks demonstrate that this distillation approach effectively addresses the bottleneck of leveraging past exploratory efforts.

## Key Contributions

- Introduces TimeClaw, an exploratory execution learning framework that enables AI agents to learn from diverse candidate execution paths in time-series tasks.
- Implements a four-stage loop (Explore, Compare, Distill, Reinject) that avoids online test-time adaptation while keeping base model weights frozen.
- Achieves consistent performance improvements across 17 diverse finance and weather prediction tasks compared to current LLM-based agentic baselines.

## Open Questions & Future Work

- [[learning-from-execution-quality-in-numeric-tasks]]
- [[mitigating-exploration-time-tool-prior-collapse]]

## Key Concepts

- [[timeclaw]]: An exploratory execution learning framework for time-series analysis that distills multi-candidate execution paths into hierarchical, reusable experiences.

## Archivist Review

I approved the core framework 'TimeClaw' for its novel distillation-based approach to agentic execution learning. I also approved two research questions that identify critical bottlenecks in scaling numeric reasoning: the challenge of quantifying execution quality and the prevention of tool-prior collapse during exploration.

### Approved Concepts
- TimeClaw: The framework introduces a novel four-stage loop (Explore, Compare, Distill, and Reinject) to turn exploratory time-series execution into reusable experience.

### Approved Open Questions
- Learning from Quantitative Execution Quality: This is critical for scaling AI agents in scientific and numeric fields where the accuracy of the result is as important as the completion of the task, and where manual prompt engineering is insufficient to capture optimal tool-use patterns.
- Mitigating Tool-Prior Collapse: Unresolved tool-prior collapse severely limits the agent's ability to learn across diverse datasets, as the agent fails to discover potentially more efficient or accurate tool combinations once it has prematurely converged on a sub-optimal subset.

## Links

- [Abstract](https://arxiv.org/abs/2605.10038)
- [PDF](https://arxiv.org/pdf/2605.10038)

