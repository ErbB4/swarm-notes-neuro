---
# CSL-compatible fields
title: "Generative Diffusion Prior Distillation for Long-Context Knowledge Transfer"
author:
  - literal: "Nilushika Udayangani"
  - literal: "Kishor Nandakishor"
  - literal: "M. Palaniswami"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11414"

# Custom fields
paper_id: "2605.11414"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "knowledge-distillation"
  - "diffusion-models"
  - "representation-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "generative-diffusion-prior-distillation-gdpd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:36Z"
created_at: "2026-05-15T06:15:36Z"
---

# Generative Diffusion Prior Distillation for Long-Context Knowledge Transfer

**Authors**: Nilushika Udayangani, Kishor Nandakishor, M. Palaniswami
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11414](https://arxiv.org/abs/2605.11414)

## Summary

This paper addresses the performance degradation of time-series classifiers when restricted to partial sequence prefixes. The authors propose Generative Diffusion Prior Distillation (GDPD), which reframes partial sequence learning as an iterative restoration problem. By learning a diffusion-based generative prior over full-context teacher representations, the framework provides students with task-relevant long-range signals to mitigate the absence of discriminative patterns in early-stage data. Experiments confirm that GDPD effectively enhances the generalization of partial classifiers by leveraging full-sequence knowledge distillation.

## Key Contributions

- Introduces Generative Diffusion Prior Distillation (GDPD), a knowledge distillation framework that bridges the performance gap between short-context and full-context time-series classifiers.
- Treats partial student inputs as degraded observations of full-context teacher features, using a diffusion-based generative prior to posterior-sample and distill missing long-range information.
- Demonstrates consistent performance improvements for early classification across diverse datasets and architectures compared to conventional feature-matching distillation.

## Open Questions & Future Work

- [[generative-prior-distillation-extensions]]

## Key Concepts

- [[generative-diffusion-prior-distillation-gdpd]]: A knowledge distillation framework that uses a diffusion-based generative prior to guide partial-context student representations toward full-context teacher distributions.

## Archivist Review

Approved GDPD as a novel, reusable distillation mechanism that shifts from simple feature matching to generative prior restoration. Approved the open question regarding distillation extensions to broaden the scope of this technique, while rejecting the domain-specific application to text as too speculative and low-impact.

### Approved Concepts
- Generative Diffusion Prior Distillation (GDPD): Introduces a novel paradigm for knowledge distillation in time-series by modeling partial context as a degraded observation of full-context features using diffusion priors.

### Approved Open Questions
- Generative Prior Distillation Extensions: This addresses the fundamental limitation of cross-context alignment in distillation, which is crucial for transfer learning in various sequential domains.

### Rejected Candidates
- [open_question] Generative Prior Distillation for Text (`generative-prior-distillation-text`) - low_impact: The proposed question is too domain-specific and speculative regarding cross-modality (text) extension rather than addressing a fundamental bottleneck in the mechanism itself.

## Links

- [Abstract](https://arxiv.org/abs/2605.11414)
- [PDF](https://arxiv.org/pdf/2605.11414)

