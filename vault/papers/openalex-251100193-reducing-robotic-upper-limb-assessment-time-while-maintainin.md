---
# CSL-compatible fields
title: "Reducing robotic upper-limb assessment time while maintaining precision: a time series foundation model approach"
author:
  - literal: "Faranak Akbarifar"
  - literal: "Nooshin Maghsoodi"
  - literal: "Sean P. Dukelow"
  - literal: "Stephen Scott"
  - literal: "Parvin Mousavi"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2511.00193"

# Custom fields
paper_id: "2511.00193"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-augmented-generation"
  - "forecasting"
  - "clinical-applications"
architectures:
  []
datasets:
  []
concept_slugs:
  - "time-series-augmented-generation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:57:03Z"
created_at: "2026-05-09T05:57:03Z"
---

# Reducing robotic upper-limb assessment time while maintaining precision: a time series foundation model approach

**Authors**: Faranak Akbarifar, Nooshin Maghsoodi, Sean P. Dukelow, Stephen Scott, Parvin Mousavi
**Date**: 2026-05-06
**Paper ID**: [openalex:2511.00193](https://arxiv.org/abs/2511.00193)

## Summary

This study addresses the clinical fatigue and time burden of Visually Guided Reaching (VGR) robotic assessments by using time series foundation models to generate synthetic reaching trials. By fine-tuning models like Chronos on an early subset of data (8-16 reaches), the researchers successfully recovered kinematic biomarkers comparable to full-session recordings. The resulting forecast-augmented paradigm significantly shortens assessment times, particularly benefiting stroke survivors, without compromising the reliability of standard Kinarm kinematic metrics.

## Key Contributions

- Demonstrates that foundation-model-based forecasting (Chronos) can replace approximately 60-80% of recorded reaching trials in Kinarm VGR assessments while maintaining high ICC agreement with full-session benchmarks.
- Establishes that augmenting 8 recorded trials with synthetic trials achieves agreement levels typically requiring 24-28 actual reaching trials, reducing assessment time for stroke patients from 4-5 minutes to ~1 minute.
- Benchmarks foundation models (Chronos, MOMENT) against statistical baselines (ARIMA) for synthetic kinematic data generation in clinical robotic environments.

## Open Questions & Future Work

- [[biomechanically-informed-foundation-models]]

## Key Concepts

- [[time-series-augmented-generation]]: A paradigm where foundation-model-generated synthetic trials augment limited recorded data to preserve clinical assessment fidelity.

## Archivist Review

The paper presents a clear and novel clinical application of foundation-model-based time-series forecasting. I approved 'Time Series Augmented Generation' as it provides a valuable, reusable framework for clinical assessment, and the open question regarding 'Biomechanical Interpretation of Models' as it addresses a fundamental limitation in using black-box foundation models for physiological diagnostics. Other candidates were rejected for being overly task-specific or routine future work.

### Approved Concepts
- Time Series Augmented Generation: The paper demonstrates that synthetic trial generation via foundation models can reduce clinical assessment time while maintaining diagnostic precision.

### Approved Open Questions
- Biomechanical Interpretation of Models: Improving model interpretability is critical for clinical acceptance and understanding the pathological mechanisms of motor impairment following stroke, beyond mere statistical performance.

### Rejected Candidates
- [open_question] Extending Forecasting to Batteries (`extending-forecasting-to-full-batteries`) - low_impact: This is essentially a request for more experiments on different tasks, which does not constitute a fundamental, unresolved bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2511.00193)
- [PDF](https://arxiv.org/pdf/2511.00193)

