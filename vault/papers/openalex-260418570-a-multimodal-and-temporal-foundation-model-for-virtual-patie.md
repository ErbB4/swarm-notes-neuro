---
# CSL-compatible fields
title: "A multimodal and temporal foundation model for virtual patient representations at healthcare system scale"
author:
  - literal: "Andrew Zhang"
  - literal: "Tong Ding"
  - literal: "Sophia Wagner"
  - literal: "Caiwei Tian"
  - literal: "Ming Y. Lu"
  - literal: "R. Pettit"
  - literal: "Joshua E. Lewis"
  - literal: "Alexandre Misrahi"
  - literal: "Dandan Mo"
  - literal: "Long P. Le"
  - literal: "Faisal Mahmood"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18570"

# Custom fields
paper_id: "2604.18570"
paper_source: "openalex"
domain: "nlp"
tags:
  - "healthcare"
  - "foundation-models"
  - "multimodal-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "virtual-patient-representation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:49:19Z"
created_at: "2026-04-23T05:49:19Z"
---

# A multimodal and temporal foundation model for virtual patient representations at healthcare system scale

**Authors**: Andrew Zhang, Tong Ding, Sophia Wagner, Caiwei Tian, Ming Y. Lu, R. Pettit, Joshua E. Lewis, Alexandre Misrahi, Dandan Mo, Long P. Le, Faisal Mahmood
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18570](https://arxiv.org/abs/2604.18570)

## Summary

Apollo is a multi-modal temporal foundation model designed to synthesize longitudinal healthcare data into unified, compressed virtual patient representations. By integrating structured events, clinical text, and medical imaging, the model creates a comprehensive 'atlas of medical concepts' that supports computational reasoning across the entire patient care journey. Evaluation on 322 prognosis and retrieval tasks demonstrates robust performance in predicting long-term disease onset, progression, and treatment outcomes, alongside capabilities for multi-modal semantic search.

## Key Contributions

- Introduces Apollo, a multi-modal temporal foundation model trained on 25 billion records from 7.2 million patients across 28 modalities.
- Demonstrates generalization across 322 diverse clinical tasks including disease onset prediction, progression modeling, and treatment response.
- Establishes a unified representation space (atlas of medical concepts) integrating structured, text, and image clinical data.

## Key Concepts

- [[virtual-patient-representation]]: A compressed latent representation of a patient's longitudinal, multi-modal health history.

## Archivist Review

I approved 'Virtual Patient Representation' as it represents a core, reusable paradigm for multi-modal clinical foundation models. No other concepts or open questions were sufficiently novel or distinct from existing literature to justify entry into the vault. The evaluation tasks described in the paper were considered standard application-specific benchmarking rather than general methodological contributions.

### Approved Concepts
- Virtual Patient Representation: Central mechanism for encoding longitudinal, multi-modal clinical history into a latent space for downstream reasoning.

## Links

- [Abstract](https://arxiv.org/abs/2604.18570)
- [PDF](https://arxiv.org/pdf/2604.18570)

