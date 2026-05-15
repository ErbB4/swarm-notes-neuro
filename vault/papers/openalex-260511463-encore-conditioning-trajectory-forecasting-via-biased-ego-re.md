---
# CSL-compatible fields
title: "Encore: Conditioning Trajectory Forecasting via Biased Ego Rehearsals"
author:
  - literal: "Conghao Wong"
  - literal: "Ziqian Zou"
  - literal: "Xinge You"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11463"

# Custom fields
paper_id: "2605.11463"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "biased-ego-rehearsals"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:14:55Z"
created_at: "2026-05-15T06:14:55Z"
---

# Encore: Conditioning Trajectory Forecasting via Biased Ego Rehearsals

**Authors**: Conghao Wong, Ziqian Zou, Xinge You
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11463](https://arxiv.org/abs/2605.11463)

## Summary

The Encore model introduces a novel paradigm for trajectory forecasting that explicitly captures and modulates agent subjectivities, which are often ignored or treated as implicit noise in traditional models. The approach employs a two-phase process: a rehearsal phase where an ego predictor derives biased rehearsal trajectories from short-term observations, followed by an encore phase that uses these trajectories to condition the final prediction network. This structure allows the model to simulate various agent subjectivities more accurately and provides clear interpretability through the lens of biased rehearsals. Experimental results confirm that this conditioning mechanism consistently enhances trajectory prediction performance across standard benchmarks.

## Key Contributions

- Introduces the Encore model, which explicitly models and forecasts agent subjectivities in trajectory prediction through a two-phase rehearsal-to-encore process.
- Demonstrates that deriving biased rehearsal trajectories from short-term observations effectively conditions final predictions, improving accuracy compared to standard approaches.
- Provides a framework for interpretability in trajectory forecasting by visualizing learned subjectivities as structured ego biases.

## Open Questions & Future Work

- [[ego-subjectivity-modeling-limitations]]

## Key Concepts

- [[biased-ego-rehearsals]]: A conditioning mechanism for trajectory forecasting that models agent subjectivities as explicitly biased rehearsal trajectories derived from short-term observations to guide future prediction.

## Archivist Review

I approved 'Biased Ego Rehearsals' as a distinct, reusable methodology for conditioning trajectory forecasting with interpretable control signals. The open question on 'Modeling Subjectivity in Trajectories' was approved as it captures a fundamental limitation in current multi-agent forecasting research. I applied strict criteria to ensure only core contributions were captured, rejecting boilerplate future work and keeping the vault concise.

### Approved Concepts
- Biased Ego Rehearsals: The concept provides a novel, interpretability-focused conditioning mechanism for multi-agent trajectory prediction by explicitly modeling agent subjectivities as control signals.

### Approved Open Questions
- Modeling Subjectivity in Trajectories: This represents a fundamental bottleneck in achieving human-like predictability in complex social navigation scenarios, where agent subjectivity is a primary driver of anisotropic behavior.

## Links

- [Abstract](https://arxiv.org/abs/2605.11463)
- [PDF](https://arxiv.org/pdf/2605.11463)

