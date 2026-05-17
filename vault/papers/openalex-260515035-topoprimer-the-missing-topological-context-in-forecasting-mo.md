---
# CSL-compatible fields
title: "TopoPrimer: The Missing Topological Context in Forecasting Models"
author:
  - literal: "Zara Zetlin"
  - literal: "Kayhan Moharreri"
  - literal: "Maria Safi"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15035"

# Custom fields
paper_id: "2605.15035"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "topology"
  - "zero-shot-learning"
  - "foundation-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "topoprimer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:07:31Z"
created_at: "2026-05-17T06:07:31Z"
---

# TopoPrimer: The Missing Topological Context in Forecasting Models

**Authors**: Zara Zetlin, Kayhan Moharreri, Maria Safi
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.15035](https://arxiv.org/abs/2605.15035)

## Summary

TopoPrimer is a novel forecasting framework that integrates the global topological structure of time-series populations as explicit input features. By utilizing persistent homology and spectral sheaf coordinates, the model provides valuable context that complements traditional sequence-based learning. Evaluations on Chronos and TimesFM across public benchmarks like ECL demonstrate significant gains in accuracy, particularly in cold-start scenarios and during high-volatility seasonal demand spikes. The approach acts as a lightweight adapter, enabling seamless integration into both zero-shot and fine-tuned forecasting architectures.

## Key Contributions

- TopoPrimer framework provides explicit topological context (via persistent homology and spectral sheaf coordinates) to forecasting models.
- Achieves up to 7.3% MSE improvement on the ECL benchmark when applied to foundation models like Chronos and TimesFM.
- Demonstrates superior robustness during peak seasonal demand, limiting forecast degradation to 10% compared to 50% in baseline models.
- Reduces MAE by 27% in cold-start forecasting scenarios by leveraging population-level topological features.

## Open Questions & Future Work

- [[learned-filtration-metrics-tda]]

## Key Concepts

- [[topoprimer]]: A forecasting framework that injects the global topological structure of series populations as explicit input features using persistent homology and spectral sheaf coordinates.

## Archivist Review

The paper proposes a compelling topological injection framework for time-series forecasting. I approved the core TopoPrimer concept and the open question regarding learnable filtration metrics, as these represent the most substantive, reusable research trajectories. Multi-parameter persistence was rejected as it is a specific extension of the primary TDA approach already being explored within the field's ongoing research agenda.

### Approved Concepts
- TopoPrimer: The paper introduces a novel, model-agnostic method to inject population-level topological features via persistent homology and spectral sheaf coordinates, which provides a distinct inductive bias for time-series foundation models.

### Approved Open Questions
- Learned Filtration Metrics for TDA: Moving beyond fixed distance metrics is a significant hurdle in making TDA more effective for high-dimensional, non-linear forecasting data.

### Rejected Candidates
- [open_question] Multi-parameter Persistence for Forecasting (`multi-parameter-persistence-forecasting`) - duplicate_existing: The candidate suggests using multi-parameter persistence, but the fundamental challenge of defining learnable metrics (captured by the other question) is more central to the TDA-for-forecasting bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.15035)
- [PDF](https://arxiv.org/pdf/2605.15035)

