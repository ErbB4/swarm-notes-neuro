---
# CSL-compatible fields
title: "Circadian Phase Locking of Epilepsy Seizures in Wearable Data: A Single-Patient Case Study"
author:
  - literal: "Berenika Ewart-James"
  - literal: "Matthew Wragg"
  - literal: "Nawid Keshtmand"
  - literal: "Amberly Brigden"
  - literal: "Paul Marshall"
  - literal: "Raúl Santos‐Rodríguez"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18297"

# Custom fields
paper_id: "2604.18297"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "healthcare-analytics"
  - "physiological-sensing"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:48:11Z"
created_at: "2026-04-23T05:48:11Z"
---

# Circadian Phase Locking of Epilepsy Seizures in Wearable Data: A Single-Patient Case Study

**Authors**: Berenika Ewart-James, Matthew Wragg, Nawid Keshtmand, Amberly Brigden, Paul Marshall, Raúl Santos‐Rodríguez
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18297](https://arxiv.org/abs/2604.18297)

## Summary

This paper investigates the relationship between epilepsy seizure onsets and circadian rhythms derived from wearable inter-beat interval (IBI) data. By applying band-limited filtering and Hilbert-based phase estimation to 176 days of continuous wearable data, the authors identify significant circadian phase concentration for seizure events. The findings suggest that modeling physiological phase offers a more interpretable and effective bridge between continuous sensing and sparse clinical events than traditional clock-time approaches. This approach provides a foundation for enhancing seizure forecasting pipelines through multi-scale phase representation.

## Key Contributions

- Introduces a methodology for aligning discrete clinical seizure events with continuous physiological rhythms using Hilbert-based phase estimation.
- Demonstrates statistically significant circadian phase concentration of seizures in a single-patient wearable dataset.
- Provides evidence that explicit physiological phase representations offer predictive structure beyond linear clock-time baselines.

## Open Questions & Future Work

- [[multi-scale-rhythm-interaction-modelling]]
- [[nonstationary-rhythm-analysis-methods]]

## Archivist Review

The paper proposes using physiological phase (via Hilbert transform) to improve seizure forecasting, which is a domain-specific application rather than a foundational ML concept. I approved the open questions regarding multi-scale rhythm interaction and nonstationary analysis as they represent significant, reusable bottlenecks in physiological time-series forecasting.

### Approved Open Questions
- Multi-scale Rhythm Interaction Modelling: Current models often miss the multi-scale interactions that likely characterize the underlying physiological processes of epilepsy, limiting the accuracy of seizure forecasting systems.
- Nonstationary Rhythm Analysis Methods: Improving phase estimation accuracy in the presence of nonstationarity is critical for moving beyond simple, stationary assumptions in longitudinal digital health monitoring.

### Rejected Candidates
- [concept] Physiological Phase Representation (`physiological-phase-representation`) - paper_local: While useful, this is a specific application of circular statistics and signal processing phase estimation rather than a novel, reusable ML architecture or mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.18297)
- [PDF](https://arxiv.org/pdf/2604.18297)

