---
# CSL-compatible fields
title: "COTCAgent: Preventive Consultation via Probabilistic Chain-of-Thought Completion"
author:
  - literal: "Zihan Deng"
  - literal: "Xiaozhen Zhong"
  - literal: "Chuanzhi Xu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15016"

# Custom fields
paper_id: "2605.15016"
paper_source: "openalex"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "healthbench"
concept_slugs:
  - "probabilistic-chain-of-thought-completion"
  - "temporal-statistics-adapter"
dataset_slugs:
  - "healthbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:08:52Z"
created_at: "2026-05-17T06:08:52Z"
---

# COTCAgent: Preventive Consultation via Probabilistic Chain-of-Thought Completion

**Authors**: Zihan Deng, Xiaozhen Zhong, Chuanzhi Xu
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.15016](https://arxiv.org/abs/2605.15016)

## Summary

COTCAgent is a hierarchical framework designed to improve clinical reasoning on longitudinal electronic health records by addressing issues with statistical hallucination and long-range temporal dependency modeling. The system utilizes a Temporal-Statistics Adapter to perform quantitative trend analysis via executable code, alongside a Chain-of-Thought Completion layer that enforces structured evidentiary reasoning. By decoupling these tasks, the framework achieves high-accuracy diagnostic inference with lower computational overhead compared to multi-modal alternatives. Evaluation on internal datasets and HealthBench confirms the model's superior performance in reliable clinical decision support.

## Key Contributions

- Proposes COTCAgent, a hierarchical reasoning framework that decouples statistical computation, feature matching, and language generation for longitudinal EHR analysis.
- Introduces the Temporal-Statistics Adapter (TSA) to convert analytical plans into executable code for standardized clinical trend output.
- Achieves 90.47% Top-1 accuracy on a self-built EHR dataset and 70.41% on HealthBench, outperforming standard LLM-based medical agents.

## Open Questions & Future Work

- [[clinical-utility-vs-benchmark-performance]]

## Key Concepts

- [[probabilistic-chain-of-thought-completion]]: A hierarchical reasoning layer that uses a weighted symptom-trend-disease knowledge base to guide clinical risk assessment in longitudinal EHR.
- [[temporal-statistics-adapter]]: A module that translates clinical reasoning plans into executable code to derive standardized, accurate trend metrics from raw longitudinal data.

## Archivist Review

I have approved the core hierarchical reasoning framework's components (the adapter and the completion layer) as they provide a reusable pattern for integrating statistical code-generation into EHR foundation models. I have also approved the 'clinical-utility-vs-benchmark-performance' open question, as it highlights a persistent, significant bottleneck in the field of clinical AI. HealthBench is included as a critical, named benchmark for evaluating such models.

### Approved Concepts
- Probabilistic Chain-of-Thought Completion: Addresses the limitation of LLMs in reasoning over long-range, non-uniform temporal EHR data by decoupling statistical computation and reasoning.
- Temporal-Statistics Adapter: Provides a reusable mechanism for LLMs to generate reliable trend analysis by offloading quantitative computation to structured code rather than relying on inherent language generation.

### Approved Open Questions
- Clinical Utility vs Benchmarking: The distinction between benchmark performance and real-world clinical reliability is a critical, unresolved obstacle for the adoption of medical foundation models.

### Rejected Candidates
- [concept] Probabilistic Chain-of-Thought Completion (`probabilistic-chain-of-thought-completion`) - other: This candidate was retained, but I am formalizing the TSA as the second concept to capture the core decoupling mechanism.

## Datasets

- [[healthbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.15016)
- [PDF](https://arxiv.org/pdf/2605.15016)

