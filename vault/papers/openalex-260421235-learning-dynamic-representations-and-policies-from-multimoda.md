---
# CSL-compatible fields
title: "Learning Dynamic Representations and Policies from Multimodal Clinical Time-Series with Informative Missingness"
author:
  - literal: "Zihan Liang"
  - literal: "Ziwen Pan"
  - literal: "Ruoxuan Xiong"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21235"

# Custom fields
paper_id: "2604.21235"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series"
  - "multimodal"
  - "healthcare"
  - "representation-learning"
  - "reinforcement-learning"
architectures:
  []
datasets:
  - "mimic-iii"
  - "eicu"
concept_slugs:
  - "informative-missingness-representation-learning"
dataset_slugs:
  - "mimic-iii"
  - "eicu"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:06Z"
created_at: "2026-04-26T05:52:06Z"
---

# Learning Dynamic Representations and Policies from Multimodal Clinical Time-Series with Informative Missingness

**Authors**: Zihan Liang, Ziwen Pan, Ruoxuan Xiong
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21235](https://arxiv.org/abs/2604.21235)

## Summary

This paper presents a framework for learning latent patient representations from multimodal clinical data (structured measurements and clinical notes) by explicitly modeling informative missingness. By integrating a multimodal encoder with a Bayesian filtering mechanism, the approach treats the act of recording data—which often correlates with patient condition—as a diagnostic feature in itself. The framework demonstrates robust performance in both predicting adverse outcomes and optimizing offline treatment policies across major ICU datasets, outperforming standard baselines that ignore the clinical context of missingness.

## Key Contributions

- Proposed a multimodal representation framework that treats clinical observation patterns as informative signals to characterize latent patient states.
- Integrated a Bayesian filtering module to update patient states dynamically based on sparse, irregular multimodal input streams.
- Achieved significant performance improvements in offline reinforcement learning and outcome prediction, reaching 0.679 FQE on MIMIC-III treatment policy evaluation.

## Open Questions & Future Work

- [[informative-missingness-multimodal-dynamics]]

## Key Concepts

- [[informative-missingness-representation-learning]]: A representation learning framework that treats the timing and pattern of clinical observations as informative signals of patient health status.

## Archivist Review

I have approved the concept of leveraging informative missingness as a representation learning strategy, as it directly addresses a critical and often overlooked temporal inductive bias in clinical data. I have also approved the corresponding open question regarding the dynamic integration of these patterns, as it remains a substantial bottleneck. The datasets MIMIC-III and eICU are included due to their status as standard, critical benchmarks for this domain. The multitask transfer question was rejected as being too generic to the field of multi-task learning.

### Approved Concepts
- Informative Missingness Representation Learning: The framework explicitly encodes the observation process itself as a diagnostic signal, which is a departure from standard imputation-based approaches.

### Approved Open Questions
- Learning from Multimodal Informative Missingness: This is a core challenge in clinical machine learning, as most existing models treat missing data merely as a technical problem to be imputed, rather than as a source of clinical signal.

### Rejected Candidates
- [open_question] Mitigating Negative Multitask Transfer (`mitigating-negative-transfer-clinical-multitask`) - not_novel: This is a generic challenge in multitask learning and not specific enough to the innovations proposed in this paper.

## Datasets

- [[mimic-iii]]
- [[eicu]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21235)
- [PDF](https://arxiv.org/pdf/2604.21235)

