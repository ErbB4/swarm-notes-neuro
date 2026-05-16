---
# CSL-compatible fields
title: "Stable Attention Response for Reliable Precipitation Nowcasting"
author:
  - literal: "Penhgui Wen"
  - literal: "Zexin Hu"
  - literal: "Sen Zhang"
  - literal: "Patrick Filippi"
  - literal: "Xiaogang Zhu"
  - literal: "Allen Benter"
  - literal: "Thomas Bishop"
  - literal: "Zhiyong Wang"
  - literal: "Kun Hu"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13181"

# Custom fields
paper_id: "2605.13181"
paper_source: "openalex"
domain: "nlp"
tags:
  - "attention-mechanism"
  - "precipitation-nowcasting"
  - "forecasting"
  - "regularization"
architectures:
  []
datasets:
  []
concept_slugs:
  - "harecast"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:02:02Z"
created_at: "2026-05-16T06:02:02Z"
---

# Stable Attention Response for Reliable Precipitation Nowcasting

**Authors**: Penhgui Wen, Zexin Hu, Sen Zhang, Patrick Filippi, Xiaogang Zhu, Allen Benter, Thomas Bishop, Zhiyong Wang, Kun Hu
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13181](https://arxiv.org/abs/2605.13181)

## Summary

This paper identifies that cross-sample instability in attention-response energy is a major, previously overlooked cause of unreliability in precipitation nowcasting. The authors theoretically show that this instability propagates through self-attention layers to increase prediction error. They propose HARECast, a regularization framework that minimizes head-wise energy fluctuations across samples, and demonstrate its effectiveness by achieving state-of-the-art results on the SEVIR and MeteoNet datasets.

## Key Contributions

- Identified cross-sample instability of attention-response energy as a critical, underexplored source of unreliability in precipitation nowcasting.
- Developed HARECast, a head-wise regularization framework that minimizes attention response energy variance to stabilize forecasts.
- Achieved state-of-the-art performance on SEVIR and MeteoNet benchmarks using HARECast with a diffusion-based predictive model.

## Open Questions & Future Work

- [[stability-vs-adaptability-nowcasting]]

## Key Concepts

- [[harecast]]: A framework that stabilizes precipitation nowcasting by regularizing head-wise attention-response energy across samples.

## Archivist Review

The paper introduces an interesting perspective on attention instability as a source of forecasting error. I approved the HARECast mechanism for its potential reusability as a regularization technique in transformer-based time-series forecasting. The open question regarding the stability-adaptability trade-off is well-posed and addresses a fundamental tension in robust model design. I rejected the datasets as they are already standard benchmarks.

### Approved Concepts
- HARECast: It introduces a novel regularization objective to minimize cross-sample attention response energy instability, directly addressing a new source of forecasting unreliability identified by the paper.

### Approved Open Questions
- Stability versus Adaptability Trade-off: This addresses the fundamental tension between model stability (low variance) and capacity (high adaptability to diverse regimes) in deep forecasting models, which is critical for real-world meteorological reliability.

## Links

- [Abstract](https://arxiv.org/abs/2605.13181)
- [PDF](https://arxiv.org/pdf/2605.13181)

