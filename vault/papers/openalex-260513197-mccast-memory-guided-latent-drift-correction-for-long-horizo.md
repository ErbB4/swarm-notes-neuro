---
# CSL-compatible fields
title: "McCast: Memory-Guided Latent Drift Correction for Long-Horizon Precipitation Nowcasting"
author:
  - literal: "Penghui Wen"
  - literal: "Yu Luo"
  - literal: "Lintao Wang"
  - literal: "Mengwei He"
  - literal: "Patrick Filippi"
  - literal: "Thomas Francis Bishop"
  - literal: "Zhiyong Wang"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13197"

# Custom fields
paper_id: "2605.13197"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "spatio-temporal-forecasting"
  - "latent-dynamics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "drift-corrective-memory-bank-dcbank"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:02:10Z"
created_at: "2026-05-16T06:02:10Z"
---

# McCast: Memory-Guided Latent Drift Correction for Long-Horizon Precipitation Nowcasting

**Authors**: Penghui Wen, Yu Luo, Lintao Wang, Mengwei He, Patrick Filippi, Thomas Francis Bishop, Zhiyong Wang
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13197](https://arxiv.org/abs/2605.13197)

## Summary

McCast addresses the long-standing issue of error accumulation in autoregressive precipitation nowcasting by introducing a memory-guided drift correction mechanism. Unlike methods that focus exclusively on improving individual step-wise accuracy, this approach uses a Drift-Corrective Memory Bank (DCBank) to actively calibrate the latent trajectory throughout the rollout. By extracting and refining drift corrections using historical memory, McCast maintains physically plausible evolution trajectories over extended forecasting horizons. Experiments on the SEVIR and MeteoNet benchmarks confirm that the model significantly improves temporal coherence and performance for long-range predictions.

## Key Contributions

- Introduces McCast, a memory-guided latent drift correction framework that explicitly calibrates autoregressive trajectory divergence in precipitation nowcasting.
- Develops the Drift-Corrective Memory Bank (DCBank), utilizing a two-stage process of corrective latent extraction and memory-based refinement to maintain temporal consistency over long horizons.
- Achieves state-of-the-art performance on the SEVIR and MeteoNet benchmarks, demonstrating superior long-horizon forecasting reliability compared to existing step-wise improvement methods.

## Open Questions & Future Work

- [[long-horizon-physical-consistency-nowcasting]]

## Key Concepts

- [[drift-corrective-memory-bank-dcbank]]: A memory-based mechanism that explicitly estimates and applies temporally consistent drift corrections to latent states during long-horizon rollouts.

## Archivist Review

The paper's proposed drift correction mechanism for autoregressive latent states is a significant, reusable contribution to the literature on long-horizon forecasting. I approved the core DCBank concept and a foundational open question regarding the tension between data-driven correction and physical consistency in extended forecast rollouts. Datasets were rejected as they are widely used benchmarks.

### Approved Concepts
- Drift-Corrective Memory Bank (DCBank): Central mechanism for mitigating error accumulation in autoregressive latent evolution.

### Approved Open Questions
- Long-Horizon Physical Consistency Nowcasting: This is critical because autoregressive drift is a fundamental bottleneck in nowcasting; addressing this via longer-horizon stability and physical consistency is essential for transitioning models to operational tools.

## Links

- [Abstract](https://arxiv.org/abs/2605.13197)
- [PDF](https://arxiv.org/pdf/2605.13197)

