---
# CSL-compatible fields
title: "DT-Transformer: A Foundation Model for Disease Trajectory Prediction on a Real-world Health System"
author:
  - literal: "Yunying Zhu"
  - literal: "Andrew R. Weckstein"
  - literal: "Kueiyu Joshua Lin"
  - literal: "Jie Yang"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14227"

# Custom fields
paper_id: "2605.14227"
paper_source: "openalex"
domain: "nlp"
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
processed_at: "2026-05-17T06:08:44Z"
created_at: "2026-05-17T06:08:44Z"
---

# DT-Transformer: A Foundation Model for Disease Trajectory Prediction on a Real-world Health System

**Authors**: Yunying Zhu, Andrew R. Weckstein, Kueiyu Joshua Lin, Jie Yang
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14227](https://arxiv.org/abs/2605.14227)

## Summary

DT-Transformer is a foundation model designed for longitudinal disease trajectory prediction within large, multi-hospital health systems. By leveraging 57.1M structured EHR entries from the Mass General Brigham network, the model effectively addresses the limitations of single-hospital research cohorts. It achieves high discriminative performance across nearly 900 disease categories, providing a robust framework for real-world clinical forecasting and early intervention.

## Key Contributions

- Introduces DT-Transformer, a foundation model for EHR data trained on a large-scale, multi-hospital dataset of 1.7M patients.
- Achieves a median AUC of 0.871 for next-event prediction across 896 clinical disease categories.
- Demonstrates the scalability and generalizability of health system-wide EHR foundation models in both retrospective and prospective validation settings.

## Open Questions & Future Work

- [[long-horizon-clinical-forecasting-decay]]
- [[clinical-utility-evaluation-paradigm]]

## Archivist Review

The paper describes a large-scale application of Transformer architectures to EHR data. I approved two open questions that characterize specific, critical bottlenecks in clinical foundation modeling: the performance decay over long horizons and the transition from predictive AUC performance to actionable clinical utility. No new concepts were approved as the model architecture is a standard Transformer application to EHR sequences.

### Approved Open Questions
- Long-horizon clinical forecasting decay: This addresses a core bottleneck in the deployment of foundation models for disease progression, where long-term clinical utility depends on maintaining predictive accuracy beyond the next immediate event.
- Clinical utility evaluation paradigm: Transitioning from predictive discriminative performance to actionable clinical utility is a fundamental challenge for the long-term viability of clinical foundation models.

### Rejected Candidates
- [open_question] Improving Long-Horizon Forecasting (`improving-long-horizon-forecasting`) - other: Renamed to better reflect the underlying research bottleneck and avoid generic phrasing.
- [open_question] Validating Clinical Utility (`clinical-utility-validation`) - other: Renamed to better reflect the methodological nature of the evaluation challenge.

## Links

- [Abstract](https://arxiv.org/abs/2605.14227)
- [PDF](https://arxiv.org/pdf/2605.14227)

