---
# CSL-compatible fields
title: "Benchmarking Sensor-Fault Robustness in Forecasting"
author:
  - literal: "Alexander Windmann"
  - literal: "Philipp Wittenberg"
  - literal: "Gianluca Manca"
  - literal: "Marcel Dix"
  - literal: "Jens U. Brandt"
  - literal: "Oliver Niggemann"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10822"

# Custom fields
paper_id: "2605.10822"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "robustness"
  - "cyber-physical-systems"
  - "benchmarking"
  - "sensor-faults"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sensorfault-bench"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:33Z"
created_at: "2026-05-14T06:09:33Z"
---

# Benchmarking Sensor-Fault Robustness in Forecasting

**Authors**: Alexander Windmann, Philipp Wittenberg, Gianluca Manca, Marcel Dix, Jens U. Brandt, Oliver Niggemann
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10822](https://arxiv.org/abs/2605.10822)

## Summary

This paper introduces SensorFault-Bench, a comprehensive benchmarking framework designed to evaluate the robustness of time-series forecasting models against sensor faults in cyber-physical systems. By incorporating a severity-based fault taxonomy and a disjoint fault-transfer evaluation split, the authors demonstrate that standard clean-data metrics often fail to predict performance degradation under fault conditions. Empirical results show that specialized robustness methods like adversarial training and fault augmentation offer targeted improvements depending on the underlying nature of the sensor fault.

## Key Contributions

- Introduces SensorFault-Bench, a standardized stress-test protocol and taxonomy for evaluating sensor-fault robustness in cyber-physical system forecasting.
- Demonstrates that models optimized for nominal (clean) performance often exhibit sharp degradation under fault scenarios, indicating a misalignment between standard metrics and robustness requirements.
- Provides a fault-transfer evaluation split and a severity model, revealing that adversarial training effectively mitigates value-based faults, while fault augmentation excels against availability-based faults.

## Open Questions & Future Work

- [[cps-forecasting-robustness-tradeoffs]]

## Key Concepts

- [[sensorfault-bench]]: A standardized stress-test protocol and taxonomy for evaluating time-series forecasting model robustness against cyber-physical system sensor faults.

## Archivist Review

I have approved the benchmarking protocol (SensorFault-Bench) as it provides a valuable, reusable methodology for time-series forecasting robustness. I also included the open question regarding robustness trade-offs, as it identifies a substantive research bottleneck in cyber-physical system modeling. Other candidates were either routine or redundant.

### Approved Concepts
- SensorFault-Bench: Provides a standardized protocol and taxonomy for evaluating model robustness under sensor faults in cyber-physical systems, addressing a major gap in time-series benchmarking.

### Approved Open Questions
- Robustness trade-offs in CPS forecasting: Understanding these trade-offs is critical for developing operationally reliable CPS forecasting models, as clean-data performance is often a poor predictor of robustness under realistic sensing failures.

## Links

- [Abstract](https://arxiv.org/abs/2605.10822)
- [PDF](https://arxiv.org/pdf/2605.10822)

