---
# CSL-compatible fields
title: "SciPaths: Forecasting Pathways to Scientific Discovery"
author:
  - literal: "Eric Chamoun"
  - literal: "Yizhou Chi"
  - literal: "Yulong Chen"
  - literal: "Rui Cao"
  - literal: "Zifeng Ding"
  - literal: "Michalis Korakakis"
  - literal: "Andreas Vlachos"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14600"

# Custom fields
paper_id: "2605.14600"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "scipaths"
concept_slugs:
  - "discovery-pathway-forecasting"
dataset_slugs:
  - "scipaths"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:07:45Z"
created_at: "2026-05-17T06:07:45Z"
---

# SciPaths: Forecasting Pathways to Scientific Discovery

**Authors**: Eric Chamoun, Yizhou Chi, Yulong Chen, Rui Cao, Zifeng Ding, Michalis Korakakis, Andreas Vlachos
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14600](https://arxiv.org/abs/2605.14600)

## Summary

The paper introduces discovery pathway forecasting, a new evaluation task that challenges models to reason backward from a target scientific contribution to the specific enabling building blocks and prior-work dependencies that make it feasible. The authors contribute the SciPaths benchmark, which includes expert-annotated and silver-standard pathways from machine learning and NLP literature. Evaluation of frontier language models reveals significant limitations in recovering methodological dependencies, highlighting a critical gap in current scientific AI capabilities.

## Key Contributions

- Introduces discovery pathway forecasting, a task focusing on identifying enabling scientific contributions and their grounding in prior work.
- Presents SciPaths, a benchmark consisting of 262 expert-annotated gold pathways and 2,444 silver pathways within the ML and NLP domains.
- Demonstrates that current frontier LLMs perform poorly on this task (0.189 F1), identifying methodological dependency recovery as a major bottleneck.

## Open Questions & Future Work

- [[scientific-pathway-decomposition-limitations]]

## Key Concepts

- [[discovery-pathway-forecasting]]: A forecasting task that identifies the necessary enabling contributions and prior-work dependencies required to realize a target scientific contribution.

## Archivist Review

I approved the novel task of discovery pathway forecasting and the SciPaths dataset, as they provide a structured framework for evaluating backward causal reasoning in scientific AI. I also approved an open question regarding decomposition limitations, as it captures a critical bottleneck identified by the authors. Other candidates were rejected to maintain the vault's high bar for novelty and impact.

### Approved Concepts
- Discovery Pathway Forecasting: It defines a novel task that moves beyond simple citation prediction to focus on backward causal reasoning of scientific dependencies.

### Approved Open Questions
- Scientific Pathway Decomposition Limitations: Improving decomposition accuracy is identified as a primary bottleneck for end-to-end scientific pathway recovery and automated scientific planning, as accurate grounding depends fundamentally on having correct enabling search targets.

## Datasets

- [[scipaths]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14600)
- [PDF](https://arxiv.org/pdf/2605.14600)

