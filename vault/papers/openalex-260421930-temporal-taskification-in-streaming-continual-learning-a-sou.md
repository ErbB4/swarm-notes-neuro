---
# CSL-compatible fields
title: "Temporal Taskification in Streaming Continual Learning: A Source of Evaluation Instability"
author:
  - literal: "Nicolae Filat"
  - literal: "Ahmed Hussain"
  - literal: "Konstantinos Kalogiannis"
  - literal: "Elena Burceanu"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21930"

# Custom fields
paper_id: "2604.21930"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "cesnet-timeseries24"
concept_slugs:
  - "boundary-profile-sensitivity"
dataset_slugs:
  - "cesnet-timeseries24"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:48Z"
created_at: "2026-04-26T05:52:48Z"
---

# Temporal Taskification in Streaming Continual Learning: A Source of Evaluation Instability

**Authors**: Nicolae Filat, Ahmed Hussain, Konstantinos Kalogiannis, Elena Burceanu
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21930](https://arxiv.org/abs/2604.21930)

## Summary

This paper identifies temporal taskification as a critical, non-neutral variable in streaming continual learning (CL) evaluation. The authors show that varying temporal splits on the same data stream leads to significantly different performance metrics, such as forgetting and backward transfer. To address this instability, they introduce Boundary-Profile Sensitivity (BPS), a metric designed to quantify the sensitivity of a streaming regime to boundary perturbations prior to model training. Experiments on the CESNET-Timeseries24 dataset confirm that taskification choice fundamentally alters benchmark conclusions, necessitating its formal inclusion as a core evaluation variable.

## Key Contributions

- Demonstrates that temporal taskification (splitting streams into discrete tasks) significantly impacts evaluation outcomes such as forecasting error and catastrophic forgetting.
- Introduces Boundary-Profile Sensitivity (BPS) to diagnose the structural sensitivity of streaming tasks to temporal boundary perturbations before model training.
- Provides empirical evidence that shorter taskification windows increase regime noise and sensitivity, challenging the neutrality of standard evaluation protocols in streaming continual learning.

## Open Questions & Future Work

- [[robust-streaming-taskification-design]]

## Key Concepts

- [[boundary-profile-sensitivity]]: A diagnostic metric that measures how sensitive a continual learning regime's structure is to small variations in temporal task boundaries.

## Archivist Review

I approved Boundary-Profile Sensitivity as a novel diagnostic tool for evaluating robustness in streaming continual learning. I also included the CESNET-Timeseries24 dataset and the identified open question regarding robust taskification, as these address significant reproducibility issues in the field. Other candidates were considered but deemed less central to the broader evolution of streaming benchmarking.

### Approved Concepts
- Boundary-Profile Sensitivity: Provides a quantitative metric to assess the stability of streaming benchmarks against temporal partitioning choices.

### Approved Open Questions
- Robust Temporal Taskification Design: This is technically significant because it addresses the core issue of benchmark reproducibility and comparability in continual learning, ensuring that observed performance gains are reflective of algorithmic improvements rather than artifactual task boundaries.

## Datasets

- [[cesnet-timeseries24]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21930)
- [PDF](https://arxiv.org/pdf/2604.21930)

