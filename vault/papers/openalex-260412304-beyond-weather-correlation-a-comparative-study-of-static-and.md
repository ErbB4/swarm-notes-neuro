---
# CSL-compatible fields
title: "Beyond Weather Correlation: A Comparative Study of Static and Temporal Neural Architectures for Fine-Grained Residential Energy Consumption Forecasting in Melbourne, Australia"
author:
  - literal: "Prasad Nimantha Madusanka Ukwatta Hewage"
  - literal: "Hao Wu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12304"

# Custom fields
paper_id: "2604.12304"
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
processed_at: "2026-04-17T05:46:19Z"
created_at: "2026-04-17T05:46:19Z"
---

# Beyond Weather Correlation: A Comparative Study of Static and Temporal Neural Architectures for Fine-Grained Residential Energy Consumption Forecasting in Melbourne, Australia

**Authors**: Prasad Nimantha Madusanka Ukwatta Hewage, Hao Wu
**Date**: 2026-04-14
**Paper ID**: [openalex:2604.12304](https://arxiv.org/abs/2604.12304)

## Summary

This study evaluates the importance of temporal autocorrelation versus static meteorological features for fine-grained (5-minute) residential energy forecasting. By comparing MLP and LSTM architectures on two Melbourne households, the authors establish that sequential memory is the dominant predictor for short-term demand. The findings underscore a substantial performance gap between recurrent and static architectures in high-resolution smart meter environments.

## Key Contributions

- Demonstrated that temporal autocorrelation significantly outperforms static meteorological features for 5-minute residential energy forecasting.
- Quantified performance gaps between LSTM and MLP architectures, showing R^2 improvements of 93.8 and 45.5 percentage points for non-PV and PV-integrated households, respectively.
- Revealed that static weather-driven models implicitly capture solar generation patterns in PV-integrated dwellings.

## Open Questions & Future Work

- [[solar-disaggregation-forecasting]]
- [[federated-learning-residential-load]]

## Archivist Review

The paper provides a straightforward comparative study that lacks novel, reusable architectural concepts or methodologies distinct enough to warrant a standalone vault concept note. However, the identified future research directions regarding solar signal disentanglement and privacy-preserving federated learning represent substantial, persistent challenges in residential time-series forecasting and were therefore elevated to open questions.

### Approved Open Questions
- Solar PV Load Disaggregation: Crucial for addressing the performance bias observed when models implicitly learn solar patterns rather than true energy demand.
- Federated Learning for Residential Forecasting: Addresses the scalability-privacy trade-off inherent in residential smart grid management.

### Rejected Candidates
- [open_question] Solar PV load disaggregation forecasting (`solar-disaggregation-forecasting`) - other: This is a re-submission/rewrite of the candidate provided in the analysis; it is approved but required adjustment for the vault format.
- [open_question] Federated learning for load forecasting (`federated-learning-residential-load`) - other: This is a re-submission/rewrite of the candidate provided in the analysis; it is approved but required adjustment for the vault format.

## Links

- [Abstract](https://arxiv.org/abs/2604.12304)
- [PDF](https://arxiv.org/pdf/2604.12304)

