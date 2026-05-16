---
# CSL-compatible fields
title: "MILM: Large Language Models for Multimodal Irregular Time Series with Informative Sampling"
author:
  - literal: "Hsing-Huan Chung"
  - literal: "Shijun Li"
  - literal: "Yoav Wald"
  - literal: "Xing Han"
  - literal: "Suchi Saria"
  - literal: "Joydeep Ghosh"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13711"

# Custom fields
paper_id: "2605.13711"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "milm-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:01:22Z"
created_at: "2026-05-16T06:01:22Z"
---

# MILM: Large Language Models for Multimodal Irregular Time Series with Informative Sampling

**Authors**: Hsing-Huan Chung, Shijun Li, Yoav Wald, Xing Han, Suchi Saria, Joydeep Ghosh
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13711](https://arxiv.org/abs/2605.13711)

## Summary

MILM addresses the challenge of multimodal irregular time series (MITS) by converting heterogeneous observations into structured XML-based time-ordered triplets, enabling LLMs to process them as sequence data. The framework uses a two-stage fine-tuning strategy that first learns to predict from irregular sampling patterns alone before incorporating actual data values. Empirical results on EHR classification show that this approach effectively captures predictive signals from sampling intervals, particularly when data values are missing at prediction time.

## Key Contributions

- Introduces MILM, a framework representing multimodal irregular time series as XML-formatted time-ordered triplets for LLM fine-tuning.
- Implements a two-stage training strategy (value-redacted pre-training followed by full data training) to explicitly decouple and then integrate the predictive signals of sampling patterns and observation values.
- Demonstrates state-of-the-art performance on EHR classification tasks, proving that the model successfully exploits irregular sampling patterns as informative signals.

## Open Questions & Future Work

- [[robustness-to-sampling-distribution-shift]]

## Key Concepts

- [[milm-framework]]: A framework that represents multimodal irregular time series as time-ordered XML triplets and employs a two-stage LLM training strategy to capture both sampling patterns and numerical/textual values.

## Archivist Review

The MILM framework is approved for its novel XML-triplet approach to sequence-based modeling of irregular time series, which is a highly reusable paradigm for current LLM-for-time-series research. The open question on sampling distribution shift is approved as it addresses a fundamental challenge for irregular time series models in clinical deployment. The proposed question on extending to image modalities was rejected as it represents incremental future work rather than an unresolved theoretical or mechanistic bottleneck.

### Approved Concepts
- Multimodal Irregular Time Series Language Model (MILM): Central novel framework for handling multimodal irregular time series data by leveraging LLMs through a structured XML-based triplet representation.

### Approved Open Questions
- Robustness to Sampling Shift: Clinical models often suffer from performance degradation when deployed in environments with different data acquisition patterns; understanding and mitigating this distribution shift is a prerequisite for reliable real-world deployment.

### Rejected Candidates
- [open_question] Extending MITS to Images (`extending-mits-models-to-images`) - low_impact: This is a boilerplate future work proposal suggesting the addition of a new modality (vision) rather than a deep unresolved algorithmic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.13711)
- [PDF](https://arxiv.org/pdf/2605.13711)

