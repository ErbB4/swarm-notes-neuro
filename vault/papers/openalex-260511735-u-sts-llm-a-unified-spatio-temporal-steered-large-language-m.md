---
# CSL-compatible fields
title: "U-STS-LLM A Unified Spatio-Temporal Steered Large Language Model for Traffic Prediction and Imputation"
author:
  - literal: "Yichen Zhang"
  - literal: "Jun Li"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11735"

# Custom fields
paper_id: "2605.11735"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamic-spatio-temporal-attention-bias-generator"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:23Z"
created_at: "2026-05-15T06:15:23Z"
---

# U-STS-LLM A Unified Spatio-Temporal Steered Large Language Model for Traffic Prediction and Imputation

**Authors**: Yichen Zhang, Jun Li
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11735](https://arxiv.org/abs/2605.11735)

## Summary

U-STS-LLM is a unified framework that bridges the gap between traffic forecasting and imputation by adapting large language models (LLMs) to structured spatio-temporal domains. The model utilizes a novel Dynamic Spatio-Temporal Attention Bias Generator to inject structural graph priors directly into the LLM's attention mechanism, addressing the instability often found when applying LLMs to non-linguistic sequence tasks. By training on a joint multi-task objective with LoRA fine-tuning, the framework achieves superior performance in both long-horizon prediction and imputation compared to traditional STGNNs, while maintaining high computational efficiency.

## Key Contributions

- Introduces U-STS-LLM, a unified framework for simultaneous long-horizon traffic forecasting and high-missing-rate imputation.
- Implements a Dynamic Spatio-Temporal Attention Bias Generator that explicitly steers LLM attention with spatio-temporal graph priors, improving convergence stability.
- Achieves state-of-the-art performance on cellular traffic datasets using parameter-efficient LoRA fine-tuning and a multi-task learning objective.

## Open Questions & Future Work

- [[llm-structured-data-generalization-bottleneck]]

## Key Concepts

- [[dynamic-spatio-temporal-attention-bias-generator]]: A mechanism that injects persistent functional graphs and transient nodal states into LLM attention layers to steer sequence modeling for spatio-temporal data.

## Archivist Review

I approved the core architectural mechanism (Attention Bias Generator) because it provides a generic, reusable way to steer LLM attention with graph priors. I also approved a refined version of the open question regarding the generalization of these models, ensuring it addresses the specific bottleneck of transferring LLM capabilities to structured data domains. Other candidates were rejected to maintain the required scarcity and quality standards.

### Approved Concepts
- Dynamic Spatio-Temporal Attention Bias Generator: This provides a generalized method for injecting relational graph priors into transformer-based attention, which is critical for applying LLMs to non-linguistic structured domains.

### Approved Open Questions
- LLM structured data generalization bottleneck: This addresses the fundamental limitation of applying LLMs to structured domains, moving beyond task-specific models towards more adaptable foundation architectures.

### Rejected Candidates
- [open_question] LLM generalization to structured domains (`llm-generalization-structured-data`) - duplicate_existing: The title and slug were too generic; renamed for clarity and to better align with vault naming conventions regarding bottlenecks.

## Links

- [Abstract](https://arxiv.org/abs/2605.11735)
- [PDF](https://arxiv.org/pdf/2605.11735)

