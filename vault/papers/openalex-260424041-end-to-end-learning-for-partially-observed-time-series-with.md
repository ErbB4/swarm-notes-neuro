---
# CSL-compatible fields
title: "End-to-End Learning for Partially-Observed Time Series with PyPOTS"
author:
  - literal: "Wenjie Du"
  - literal: "Yiyuan Yang"
  - literal: "Tianxiang Zhan"
  - literal: "Qingsong Wen"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24041"

# Custom fields
paper_id: "2604.24041"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "pypots"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:02:46Z"
created_at: "2026-04-30T06:02:46Z"
---

# End-to-End Learning for Partially-Observed Time Series with PyPOTS

**Authors**: Wenjie Du, Yiyuan Yang, Tianxiang Zhan, Qingsong Wen
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24041](https://arxiv.org/abs/2604.24041)

## Summary

This tutorial introduces PyPOTS, an open-source Python ecosystem designed to address the challenge of partially-observed time series (POTS). By integrating missing-value handling directly with downstream tasks such as forecasting and classification, the framework improves reproducibility and system performance. It offers unified APIs and standardized workflows that support the entire pipeline, from data preprocessing and simulation to model evaluation. The library is intended to serve as a standard tool for both practitioners in production and researchers aiming to build extensible, domain-aware POTS solutions.

## Key Contributions

- Introduces PyPOTS, a unified open-source ecosystem integrating missing-value imputation with downstream tasks like forecasting, classification, and anomaly detection.
- Provides standardized workflows for POTS data handling, bridging the gap between missing-value simulation and robust model evaluation.
- Establishes an extensible framework enabling developers to implement domain-specific constraints and custom model architectures within a reproducible pipeline.

## Open Questions & Future Work

- [[end-to-end-pots-integration]]

## Key Concepts

- [[pypots]]: An open-source Python ecosystem designed for end-to-end data mining and machine learning on partially-observed time series (POTS).

## Archivist Review

I approved PyPOTS as a significant ecosystem-level concept for time-series research and the corresponding open question regarding end-to-end integration of missing-data handling with downstream tasks. These items represent a shift toward unified, robust time-series pipelines rather than fragmented, modular approaches. No datasets were approved as none were highlighted as primary novel benchmarks unique to this work.

### Approved Concepts
- PyPOTS: It serves as a central, standardized ecosystem for tackling partially-observed time series (POTS) problems, promoting unified research workflows.

### Approved Open Questions
- End-to-End POTS Integration: Addressing the coupling of imputation and prediction is critical for creating reliable ML models that can function effectively when missing data is a pervasive characteristic rather than a distinct preprocessing step.

### Rejected Candidates
- [concept] PyPOTS (`pypots`) - other: The candidate was approved as a concept. (Note: The instruction allows approving up to 2 concepts. I am approving it as a concept.)

## Links

- [Abstract](https://arxiv.org/abs/2604.24041)
- [PDF](https://arxiv.org/pdf/2604.24041)

