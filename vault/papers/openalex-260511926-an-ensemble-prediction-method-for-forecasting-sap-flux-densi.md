---
# CSL-compatible fields
title: "An ensemble prediction method for forecasting sap flux density and water-use in temperate trees"
author:
  - literal: "Mengyi Gong"
  - literal: "Rebecca Killick"
  - literal: "Andrew Hirons"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11926"

# Custom fields
paper_id: "2605.11926"
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
processed_at: "2026-05-15T06:15:10Z"
created_at: "2026-05-15T06:15:10Z"
---

# An ensemble prediction method for forecasting sap flux density and water-use in temperate trees

**Authors**: Mengyi Gong, Rebecca Killick, Andrew Hirons
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11926](https://arxiv.org/abs/2605.11926)

## Summary

This paper introduces an ensemble prediction pipeline that leverages sensor-based tree sap flux data and local weather station inputs for accurate daily water-use forecasting. The proposed method utilizes additive models to capture complex non-linear relationships between physiological tree responses and environmental drivers, accounting for inter-tree variability. The framework is designed for integration into real-time IoT monitoring systems to support precision irrigation management in diverse agricultural and conservation contexts. Performance is validated through field experiments involving nine distinct tree species over three consecutive growing seasons.

## Key Contributions

- Proposes an ensemble prediction framework based on additive models for daily sap flux density and tree water-use forecasting.
- Demonstrates model robustness across nine tree species and three years (2022-2024) of growing season data.
- Evaluates model performance under climate stress conditions and identifies the influence of tree size on prediction accuracy.

## Open Questions & Future Work

- [[predicting-water-use-under-heatwaves]]
- [[scaling-water-use-by-tree-size]]

## Archivist Review

The paper describes a specific application of ensemble additive models for sap flux forecasting. I rejected the proposed concept as it constitutes a common statistical ensemble practice. I approved both open questions as they identify significant, non-trivial bottlenecks in physiological forecasting under non-stationary environmental conditions and hierarchical scaling challenges.

### Approved Open Questions
- Predicting water-use during heatwaves: As heatwaves increase in frequency and severity, predicting their impact on plant water consumption is essential for sustainable irrigation management in agriculture and forestry.
- Scaling water-use by size: Scaling individual-level physiological models to stand-level estimates is a critical bottleneck for operationalizing precision irrigation and resource management.

### Rejected Candidates
- [concept] Ensemble prediction framework based on additive models (`ensemble-prediction-framework-additive-models`) - not_novel: The use of additive models for ensemble prediction is a general statistical practice rather than a novel or distinct enough mechanism to warrant a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.11926)
- [PDF](https://arxiv.org/pdf/2605.11926)

