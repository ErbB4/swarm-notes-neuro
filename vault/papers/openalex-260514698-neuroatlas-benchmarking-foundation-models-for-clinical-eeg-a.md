---
# CSL-compatible fields
title: "NeuroAtlas: Benchmarking Foundation Models for Clinical EEG and Brain-Computer Interfaces"
author:
  - literal: "Konstantinos Kontras"
  - literal: "Trui Osselaer"
  - literal: "Stylianos G. Mouslech"
  - literal: "Angeliki-Ιlektra Karaiskou"
  - literal: "Guido Gagliardi"
  - literal: "Thomas Strypsteen"
  - literal: "Mohammad Hossein Badiei"
  - literal: "Anku Rani"
  - literal: "Maarten Vanmarcke"
  - literal: "Miguel Bhagubai"
  - literal: "Chanakya Ekbote"
  - literal: "Jaedong Hwang"
  - literal: "Christos Chatzichristos"
  - literal: "Paul Pu Liang"
  - literal: "Maarten De Vos"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14698"

# Custom fields
paper_id: "2605.14698"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "neuroatlas-benchmark"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:08:07Z"
created_at: "2026-05-17T06:08:07Z"
---

# NeuroAtlas: Benchmarking Foundation Models for Clinical EEG and Brain-Computer Interfaces

**Authors**: Konstantinos Kontras, Trui Osselaer, Stylianos G. Mouslech, Angeliki-Ιlektra Karaiskou, Guido Gagliardi, Thomas Strypsteen, Mohammad Hossein Badiei, Anku Rani, Maarten Vanmarcke, Miguel Bhagubai, Chanakya Ekbote, Jaedong Hwang, Christos Chatzichristos, Paul Pu Liang, Maarten De Vos
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14698](https://arxiv.org/abs/2605.14698)

## Summary

NeuroAtlas is a comprehensive benchmark for evaluating foundation models in electroencephalography (EEG) and brain-computer interfaces (BCI), aggregating 42 datasets totaling 260,000 hours. The study evaluates both EEG-specific and generic time-series foundation models, revealing that specialized architectures do not reliably outperform generic counterparts. Furthermore, it highlights the inadequacy of standard ML metrics for clinical applications and emphasizes the need for task-specific measures such as event-level decision-making and physiological gap analysis. The findings suggest that unified EEG foundation models are not yet mature enough for plug-and-play clinical deployment.

## Key Contributions

- Introduces NeuroAtlas, the largest multi-domain EEG benchmark comprising 42 datasets and 260,000 hours of data across clinical and BCI tasks.
- Demonstrates that specialized EEG foundation models do not consistently outperform generic time-series models, challenging current architectural assumptions in the field.
- Establishes that standard ML metrics are insufficient for clinical utility and advocates for domain-specific metrics like event-level decision-making and hypnogram-derived feature analysis.

## Open Questions & Future Work

- [[standardizing-eeg-fm-evaluation]]

## Key Concepts

- [[neuroatlas-benchmark]]: A large-scale, multi-domain benchmark consisting of 42 datasets and 260,000 hours of EEG data designed to standardize clinical and BCI model evaluation.

## Archivist Review

The paper provides a much-needed standardization for a fragmented domain (EEG foundation models) by introducing the NeuroAtlas benchmark. I have approved the benchmark as a concept because it functions as a consolidated evaluation framework. The open question regarding evaluation protocols highlights the significant gap identified between academic benchmarking and actual clinical utility in this field. Other potential concepts, such as general 'clinical metrics', were rejected as they are too generic and descriptive.

### Approved Concepts
- NeuroAtlas Benchmark: It addresses a critical fragmentation in EEG model evaluation by providing a unified, large-scale, and clinically relevant benchmark.

### Approved Open Questions
- Standardizing EEG-FM Evaluation Protocols: Understanding whether EEG foundation models provide intrinsic value or simply memorize training data is crucial for their reliable deployment in clinical decision support systems.

### Rejected Candidates
- [concept] Clinical Utility Metrics for EEG (`clinical-utility-metrics`) - generic: Generic description of domain-specific evaluation metrics that does not constitute a reusable technical framework.

## Links

- [Abstract](https://arxiv.org/abs/2605.14698)
- [PDF](https://arxiv.org/pdf/2605.14698)

