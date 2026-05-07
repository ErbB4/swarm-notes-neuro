---
# CSL-compatible fields
title: "Forecasting-Driven Stable Successor Matching for UAV-Assisted Continuous Edge Services"
author:
  - literal: "Houyi Qi"
  - literal: "Minghui Liwang"
  - literal: "Yuhan Su"
  - literal: "Xianbin Wang"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02180"

# Custom fields
paper_id: "2605.02180"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "proactive-successor-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:04:22Z"
created_at: "2026-05-07T06:04:22Z"
---

# Forecasting-Driven Stable Successor Matching for UAV-Assisted Continuous Edge Services

**Authors**: Houyi Qi, Minghui Liwang, Yuhan Su, Xianbin Wang
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02180](https://arxiv.org/abs/2605.02180)

## Summary

This paper addresses the problem of service continuity in UAV-assisted edge networks (UENs) by proposing a proactive successor matching framework named Fresco. The approach utilizes an LSTM model to forecast potential service disruption risks caused by UAV mobility and energy depletion, triggering proactive service-context synchronization. Evaluation demonstrates that Fresco significantly reduces service interruptions compared to reactive baselines while maintaining low resource reservation overhead.

## Key Contributions

- Introduces Fresco, a forecasting-driven service scheduling framework that proactive schedules successor UAVs to mitigate service interruptions in mobile edge networks.
- Employs an LSTM-based module for predicting mission-specific disruption risks based on network observations.
- Develops an online risk-aware successor matching scheme that optimizes standby UAV selection under energy, latency, and resource constraints with minimal overhead.

## Open Questions & Future Work

- [[robust-predictive-risk-assessment-uen]]

## Key Concepts

- [[proactive-successor-matching]]: A framework design pattern for mobile edge computing that proactively reserves and synchronizes resources on standby nodes based on predicted disruption risks.

## Archivist Review

I have approved the core architectural concept of 'Proactive Successor Matching', as it represents a shift in service scheduling strategy for edge networks beyond simple reactive handovers. The open question regarding predictive robustness was approved because it addresses a fundamental reliability bottleneck in proactive resource reservation. I rejected 'Fresco' as it is a specific framework name and a routine application of existing predictive methods.

### Approved Concepts
- Proactive Successor Matching: This shift from reactive handover to proactive service reservation in edge networks is a distinct architectural pattern that is likely to see further development in mobile computing.

### Approved Open Questions
- Robust Predictive Risk Assessment: Predictive accuracy is the bottleneck for the entire proactive reservation process; if predictions are inaccurate, the system incurs unnecessary reservation overhead or fails to prepare for actual failures.

### Rejected Candidates
- [concept] Fresco (`fresco`) - paper_local: This is a specific framework name rather than a reusable concept; it is a composition of existing techniques rather than a novel mechanism itself.

## Links

- [Abstract](https://arxiv.org/abs/2605.02180)
- [PDF](https://arxiv.org/pdf/2605.02180)

