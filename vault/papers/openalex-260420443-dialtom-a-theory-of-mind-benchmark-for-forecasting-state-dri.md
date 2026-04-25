---
# CSL-compatible fields
title: "DialToM: A Theory of Mind Benchmark for Forecasting State-Driven Dialogue Trajectories"
author:
  - literal: "Neemesh Yadav"
  - literal: "Palakorn Achananuparp"
  - literal: "Jing Jiang"
  - literal: "Ee‐Peng Lim"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20443"

# Custom fields
paper_id: "2604.20443"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "dialtom"
concept_slugs:
  - "prospective-diagnostic-forecasting"
dataset_slugs:
  - "dialtom"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:37:42Z"
created_at: "2026-04-25T05:37:42Z"
---

# DialToM: A Theory of Mind Benchmark for Forecasting State-Driven Dialogue Trajectories

**Authors**: Neemesh Yadav, Palakorn Achananuparp, Jing Jiang, Ee‐Peng Lim
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20443](https://arxiv.org/abs/2604.20443)

## Summary

DialToM is a new human-verified benchmark designed to distinguish between superficial mental state recognition and robust functional reasoning in LLMs. The authors introduce Prospective Diagnostic Forecasting to evaluate whether models can leverage inferred mental states to accurately predict subsequent social dialogue trajectories. Experimental results demonstrate a clear reasoning asymmetry, where most state-of-the-art LLMs successfully identify mental states but fail to utilize them for accurate future trajectory prediction.

## Key Contributions

- Introduces DialToM, a human-verified benchmark for assessing both Literal and Functional Theory of Mind in LLMs.
- Proposes Prospective Diagnostic Forecasting to measure whether models can use mental states to predict dialogue trajectories.
- Demonstrates a reasoning asymmetry in current LLMs, where high performance on state identification does not correlate with the ability to perform functional trajectory forecasting.

## Open Questions & Future Work

- [[functional-tom-pattern-matching-bottleneck]]

## Key Concepts

- [[prospective-diagnostic-forecasting]]: A technique for evaluating Theory of Mind by requiring models to predict future dialogue trajectories conditioned on inferred mental-state profiles.

## Archivist Review

I approved the prospective diagnostic forecasting technique as a reusable evaluation methodology for latent state-driven prediction, and the DialToM dataset as a core resource for this specialized benchmark. The open question was refined to highlight the bottleneck between surface-level pattern matching and true functional reasoning in social intelligence models. The review adhered to the scarcity constraints while ensuring the methodological contributions were preserved.

### Approved Concepts
- Prospective Diagnostic Forecasting: It provides a rigorous way to test if a model can use inferred latent states (like ToM) for downstream trajectory prediction, rather than just performing pattern recognition.

### Approved Open Questions
- Isolating Functional ToM Reasoning: This distinguishes between predictive linguistic pattern matching and actual agentic reasoning, a requirement for reliable social intelligence in future models.

### Rejected Candidates
- [open_question] Isolating Functional Theory of Mind (`distinguishing-functional-tom-from-pattern-matching`) - duplicate_existing: Renamed for brevity and to align with existing vault naming conventions.

## Datasets

- [[dialtom]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20443)
- [PDF](https://arxiv.org/pdf/2604.20443)

