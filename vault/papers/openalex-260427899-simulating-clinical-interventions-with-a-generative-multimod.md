---
# CSL-compatible fields
title: "Simulating clinical interventions with a generative multimodal model of human physiology"
author:
  - literal: "Guy Lutsker"
  - literal: "Gal Sapir"
  - literal: "Jordi Merino"
  - literal: "Smadar Shilo"
  - literal: "Anastasia Godneva"
  - literal: "Eli Meirom"
  - literal: "Shie Mannor"
  - literal: "Hagai Rossman"
  - literal: "Gal Chechik"
  - literal: "Eran Segal"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27899"

# Custom fields
paper_id: "2604.27899"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "health-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:03:26Z"
created_at: "2026-05-03T06:03:26Z"
---

# Simulating clinical interventions with a generative multimodal model of human physiology

**Authors**: Guy Lutsker, Gal Sapir, Jordi Merino, Smadar Shilo, Anastasia Godneva, Eli Meirom, Shie Mannor, Hagai Rossman, Gal Chechik, Eran Segal
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27899](https://arxiv.org/abs/2604.27899)

## Summary

HealthFormer is a decoder-only transformer model designed to act as a generative world model for human physiology. By tokenizing longitudinal health trajectories across 667 diverse clinical and lifestyle variables, the model supports forecasting, risk stratification, and intervention-conditioned simulation as unified query tasks. Evaluation on independent clinical cohorts and historical trial data demonstrates its superiority over traditional clinical risk scores and its capacity to simulate individual-level responses to health interventions.

## Key Contributions

- Introduced HealthFormer, a decoder-only transformer trained on 667 physiological measurements across seven multimodal domains from 15,000 participants.
- Demonstrated zero-shot transfer capability to four independent cohorts, outperforming clinical risk scores on 27 of 30 incident-disease and mortality endpoints.
- Enabled in silico intervention simulation, accurately predicting individual biomarker changes and aligning with effect directions in 41 clinical trial benchmarks.

## Key Concepts

- [[health-world-model]]: A transformer-based foundational architecture designed to model longitudinal multimodal health data for forecasting and in silico intervention simulation.

## Archivist Review

The paper introduces a compelling framework for generative modeling of longitudinal patient physiology. I approved the 'Health World Model' concept as it defines the nascent field of large-scale generative clinical simulation. The model instance itself (HealthFormer) was rejected as being a specific implementation rather than a general methodological concept.

### Approved Concepts
- Health World Model: The concept of an architecture acting as a foundational 'world model' for complex physiological processes represents a paradigm shift from task-specific medical AI to general-purpose clinical simulation.

### Rejected Candidates
- [concept] HealthFormer (`healthformer`) - paper_local: This is a specific model implementation rather than a general, reusable concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.27899)
- [PDF](https://arxiv.org/pdf/2604.27899)

