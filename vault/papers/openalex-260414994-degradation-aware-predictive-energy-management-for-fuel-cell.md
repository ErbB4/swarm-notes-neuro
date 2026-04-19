---
# CSL-compatible fields
title: "Degradation-aware Predictive Energy Management for Fuel Cell-Battery Ship Power System with Data-driven Load Forecasting"
author:
  - literal: "Timon Kopka"
  - literal: "Sara Tamburello"
  - literal: "Luca Oneto"
  - literal: "Lindert van Biert"
  - literal: "Henk Polinder"
  - literal: "Andrea Coraddu"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14994"

# Custom fields
paper_id: "2604.14994"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:44:57Z"
created_at: "2026-04-19T05:44:57Z"
---

# Degradation-aware Predictive Energy Management for Fuel Cell-Battery Ship Power System with Data-driven Load Forecasting

**Authors**: Timon Kopka, Sara Tamburello, Luca Oneto, Lindert van Biert, Henk Polinder, Andrea Coraddu
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.14994](https://arxiv.org/abs/2604.14994)

## Summary

This paper addresses the operational cost optimization of hydrogen-based fuel cell-battery hybrid ship power systems by explicitly modeling both fuel consumption and cell degradation. The authors introduce a degradation-aware predictive energy management strategy that leverages data-driven load forecasting to optimize power dispatch. Applied to real operating data from a harbor tug, the approach significantly outperforms standard filter-based benchmarks in both fuel efficiency and component longevity across multiple prediction horizons.

## Key Contributions

- Proposed a degradation-aware predictive energy management strategy for fuel cell-battery hybrid shipboard power systems.
- Integrated data-driven load forecasting to optimize power distribution over 15min and 1h horizons.
- Demonstrated up to 5.8% reduction in hydrogen consumption and 36.4% reduction in fuel cell degradation compared to filter-based benchmarks.

## Open Questions & Future Work

- [[fuel-cell-eol-optimization]]

## Archivist Review

The paper presents a specific application of predictive energy management. I approved the question regarding EOL definition as it challenges a common modeling assumption in power system health management. The second question was rejected as a standard architectural extension (adding an outer control loop), which is common in control systems literature and doesn't represent a foundational scientific bottleneck. No concepts were sufficiently novel or reusable outside this specific domain to warrant a permanent vault entry.

### Approved Open Questions
- Fuel Cell EOL Definition: The EOL definition significantly impacts the cost model and maintenance scheduling; using a fixed threshold may lead to suboptimal lifetime management.

### Rejected Candidates
- [open_question] Multi-horizon EMS Optimization (`multi-horizon-ems-optimization`) - low_impact: The proposed future work is a standard architectural refinement rather than a fundamental unresolved bottleneck in time-series control or energy management.

## Links

- [Abstract](https://arxiv.org/abs/2604.14994)
- [PDF](https://arxiv.org/pdf/2604.14994)

