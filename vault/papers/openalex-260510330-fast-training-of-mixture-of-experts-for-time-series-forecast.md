---
# CSL-compatible fields
title: "Fast Training of Mixture-of-Experts for Time Series Forecasting via Expert Loss Integration"
author:
  - literal: "Btissame El Mahtout"
  - literal: "Florian Ziel"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10330"

# Custom fields
paper_id: "2605.10330"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "mixture-of-experts"
  - "online-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:08:51Z"
created_at: "2026-05-14T06:08:51Z"
---

# Fast Training of Mixture-of-Experts for Time Series Forecasting via Expert Loss Integration

**Authors**: Btissame El Mahtout, Florian Ziel
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10330](https://arxiv.org/abs/2605.10330)

## Summary

This paper introduces an adaptive Mixture-of-Experts (MoE) framework designed to improve time series forecasting by incorporating expert-specific loss information into the training objective. By combining this granular loss awareness with a partial online learning strategy, the model enables efficient, incremental updates to gating and expert parameters. This approach minimizes the computational demand of model maintenance while achieving high predictive performance across various temporal datasets. Empirical evaluations confirm that the proposed method consistently outperforms traditional statistical models and current neural network standards.

## Key Contributions

- Introduces an adaptive Mixture-of-Experts framework for time series that integrates expert-specific losses with global forecasting objectives to improve specialization.
- Implements a partial online learning strategy that allows for incremental updates to gating and expert parameters, significantly reducing computational overhead compared to full retraining.
- Demonstrates superior forecasting accuracy and computational efficiency over statistical baselines and state-of-the-art neural architectures (Transformers, WaveNet) on diverse economic, tourism, and energy datasets.

## Open Questions & Future Work

- [[optimal-gamma-weighting-moe]]
- [[mitigating-extreme-forecast-errors]]

## Archivist Review

I approved the two open questions as they address significant, unresolved trade-offs and stability issues inherent to MoE forecasting models. I rejected the proposed concepts because they describe implementation subcomponents that do not rise to the level of standalone vault notes.

### Approved Open Questions
- Optimal Weighting of Expert Loss: This parameter directly controls the trade-off between specialization (via expert loss) and coordination (via global loss), which is fundamental to the MoE architecture's success in time series forecasting.
- Causes of Extreme Forecast Errors: Understanding and mitigating extreme prediction errors is crucial for the reliability and risk management applications of time series forecasting models.

### Rejected Candidates
- [concept] Expert-specific loss integration (`expert-loss-integration`) - subcomponent_of_broader_mechanism: This is a specific architectural optimization technique rather than a foundational concept or reusable framework mechanism.
- [concept] Partial online learning strategy (`partial-online-learning-strategy`) - not_novel: This is a standard implementation approach for MoE models, not a novel conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2605.10330)
- [PDF](https://arxiv.org/pdf/2605.10330)

