---
# CSL-compatible fields
title: "Unlocking air traffic flow prediction through microscopic aircraft-state modeling"
author:
  - literal: "Bin Wang"
  - literal: "Anqi Liu"
  - literal: "Jiangtao Zhao"
  - literal: "Yanyong Huang"
  - literal: "Peilan He"
  - literal: "Guiyuan Jiang"
  - literal: "Feng Hong"
  - literal: "Yanwei Yu"
  - literal: "Tianrui Li"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10083"

# Custom fields
paper_id: "2605.10083"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "state-to-flow-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:14Z"
created_at: "2026-05-14T06:10:14Z"
---

# Unlocking air traffic flow prediction through microscopic aircraft-state modeling

**Authors**: Bin Wang, Anqi Liu, Jiangtao Zhao, Yanyong Huang, Peilan He, Guiyuan Jiang, Feng Hong, Yanwei Yu, Tianrui Li
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10083](https://arxiv.org/abs/2605.10083)

## Summary

AeroSense is a novel modeling framework for air traffic flow prediction that replaces traditional aggregated time-series analysis with a state-to-flow mapping approach. By representing terminal airspace as a dynamic set of microscopic aircraft states derived from ADS-B trajectories, the framework preserves fine-grained kinematic and intent-based information. This approach allows the model to predict future traffic density directly from current instantaneous conditions without needing historical look-back windows, outperforming existing forecasting baselines.

## Key Contributions

- Introduces AeroSense, a framework that maps microscopic aircraft state sets directly to future traffic flow.
- Demonstrates superior performance over aggregation-based time-series forecasting methods, especially in high-density traffic scenarios.
- Shows that instantaneous airspace snapshots can replace traditional historical look-back window requirements for accurate traffic prediction.

## Open Questions & Future Work

- [[long-term-air-traffic-forecasting]]
- [[multi-modal-air-traffic-prediction]]

## Key Concepts

- [[state-to-flow-modeling]]: A modeling paradigm that predicts aggregate traffic flow by processing instantaneous, microscopic state representations of individual agents rather than historical aggregated time series.

## Archivist Review

I approved the 'state-to-flow modeling' concept as it represents a significant methodological shift from traditional aggregated time-series forecasting. I also approved two open questions concerning horizon extension and multimodal data integration, as these address fundamental limitations in current state-based forecasting paradigms. I maintained a strict selection policy by only including high-level methodological shifts and research bottlenecks.

### Approved Concepts
- State-to-flow modeling: Moves away from traditional aggregated time-series forecasting by directly mapping microscopic individual states to macroscopic flow.

### Approved Open Questions
- Extended Air Traffic Forecasting Horizons: The current evaluation is limited to a 15-minute horizon; confirming performance at longer horizons is essential for strategic air traffic flow management.
- Multi-modal Air Traffic Prediction: Incorporating external variables is critical for robustness in volatile operational environments where state snapshots are insufficient.

## Links

- [Abstract](https://arxiv.org/abs/2605.10083)
- [PDF](https://arxiv.org/pdf/2605.10083)

