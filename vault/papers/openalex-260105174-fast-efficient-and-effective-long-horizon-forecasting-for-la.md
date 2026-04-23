---
# CSL-compatible fields
title: "FaST: Efficient and Effective Long-Horizon Forecasting for Large-Scale Spatial-Temporal Graphs via Mixture-of-Experts"
author:
  - literal: "Yiji Zhao"
  - literal: "Zihao Zhong"
  - literal: "Ao Wang"
  - literal: "Haomin Wen"
  - literal: "Ming Jin"
  - literal: "Yuxuan Liang"
  - literal: "Huaiyu Wan"
  - literal: "Hao Wu"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2601.05174"

# Custom fields
paper_id: "2601.05174"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "mixture-of-experts"
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-graph-agent-attention"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:47:48Z"
created_at: "2026-04-23T05:47:48Z"
---

# FaST: Efficient and Effective Long-Horizon Forecasting for Large-Scale Spatial-Temporal Graphs via Mixture-of-Experts

**Authors**: Yiji Zhao, Zihao Zhong, Ao Wang, Haomin Wen, Ming Jin, Yuxuan Liang, Huaiyu Wan, Hao Wu
**Date**: 2026-04-20
**Paper ID**: [openalex:2601.05174](https://arxiv.org/abs/2601.05174)

## Summary

FaST addresses the computational bottlenecks of existing spatial-temporal graph (STG) models by enabling efficient, large-scale, long-horizon forecasting. The framework utilizes an adaptive graph agent attention mechanism to replace expensive traditional graph convolutions and a novel parallel Mixture-of-Experts (MoE) structure based on Gated Linear Units. Experimental results demonstrate that FaST achieves superior long-horizon accuracy while significantly reducing computational overhead compared to current state-of-the-art baselines.

## Key Contributions

- Introduced FaST, an efficient MoE-based framework capable of 672-step long-horizon forecasting on large-scale graphs.
- Developed Adaptive Graph Agent Attention to decouple computational complexity from graph scale.
- Proposed a parallel MoE module utilizing Gated Linear Units (GLUs) for enhanced efficiency and scalability in STG forecasting.

## Open Questions & Future Work

- [[foundation-model-stg-integration-bottleneck]]

## Key Concepts

- [[adaptive-graph-agent-attention]]: An attention variant that uses graph agents to reduce computational complexity in large-scale spatial-temporal graph models.

## Archivist Review

I approved the 'Adaptive Graph Agent Attention' as it represents a specific architectural innovation for the scalability-accuracy trade-off in STG forecasting. I also introduced a more precise open question regarding the integration of foundation models into STG frameworks, as the original submission was too generic and focused on future work plans rather than a technical bottleneck. The MoE module was rejected as it is a standard deep learning architectural choice rather than a specialized contribution to time-series forecasting.

### Approved Concepts
- Adaptive Graph Agent Attention: This mechanism addresses the core limitation of scaling STG forecasting to large networks by decoupling the graph's complexity from the attention computation.

### Approved Open Questions
- Foundation Model STG Integration Bottleneck: As STG forecasting moves toward more complex, city-wide applications, foundational models offer a path to improved generalization, yet adapting them to maintain linear-time efficiency remains a challenging bottleneck.

### Rejected Candidates
- [concept] Parallel MoE Module (`parallel-moe-module`) - not_novel: Mixture-of-Experts combined with Gated Linear Units is a well-established architectural pattern in deep learning and does not warrant a novel standalone entry.

## Links

- [Abstract](https://arxiv.org/abs/2601.05174)
- [PDF](https://arxiv.org/pdf/2601.05174)

