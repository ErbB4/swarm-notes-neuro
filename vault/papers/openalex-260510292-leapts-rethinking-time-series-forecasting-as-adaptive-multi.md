---
# CSL-compatible fields
title: "LeapTS: Rethinking Time Series Forecasting as Adaptive Multi-Horizon Scheduling"
author:
  - literal: "Sheng Pan"
  - literal: "Ming Jin"
  - literal: "Bo Du"
  - literal: "Shirui Pan"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10292"

# Custom fields
paper_id: "2605.10292"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "adaptive-multi-horizon-scheduling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:08:36Z"
created_at: "2026-05-14T06:08:36Z"
---

# LeapTS: Rethinking Time Series Forecasting as Adaptive Multi-Horizon Scheduling

**Authors**: Sheng Pan, Ming Jin, Bo Du, Shirui Pan
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10292](https://arxiv.org/abs/2605.10292)

## Summary

LeapTS redefines time series forecasting by moving away from fixed history-to-target mappings, instead viewing the process as an adaptive scheduling task. It employs a hierarchical controller to determine prediction scales and advancement lengths, while utilizing neural controlled differential equations to maintain continuous-time state evolution. This approach explicitly couples irregular temporal dynamics with scheduling feedback, resulting in significant improvements in both predictive accuracy and inference speed compared to traditional Transformer-based forecasting models.

## Key Contributions

- Introduces LeapTS, a framework that reformulates time series forecasting as a dynamic multi-horizon scheduling process.
- Implements a hierarchical controller for selecting optimal prediction scales and advancement lengths at each temporal step.
- Integrates continuous-time state evolution via neural controlled differential equations to couple irregular dynamics with scheduling feedback.
- Achieves at least 7.4% improvement in forecasting performance and 2.6x-5.3x inference speedup over Transformer-based baselines.

## Open Questions & Future Work

- [[universal-scheduling-forecasting-bottleneck]]

## Key Concepts

- [[adaptive-multi-horizon-scheduling]]: A forecasting framework that treats multi-horizon prediction as a dynamic scheduling task involving the sequential selection of prediction scales and advancement lengths.

## Archivist Review

The approved concept identifies a foundational shift in how time series forecasting is modeled—moving from static mapping to dynamic scheduling—which is highly reusable. The approved open question addresses the critical transition from task-specific training to generalized scheduling foundations. Other potential candidates were excluded to maintain the vault's high barrier for entry.

### Approved Concepts
- Adaptive Multi-Horizon Scheduling: It shifts the paradigm of time series forecasting from a static mapping to a decision-making and scheduling process.

### Approved Open Questions
- Universal Scheduling Forecasting Bottleneck: This addresses the bottleneck of domain-specific training and enables better generalization, which is critical for scaling forecasting capabilities to heterogeneous real-world applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.10292)
- [PDF](https://arxiv.org/pdf/2605.10292)

