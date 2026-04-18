---
# CSL-compatible fields
title: "ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection"
author:
  - literal: "Romain Hermary"
  - literal: "Samet Hiçsönmez"
  - literal: "Dan Pineau"
  - literal: "Abd El Rahman Shabayek"
  - literal: "Djamila Aouada"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13924"

# Custom fields
paper_id: "2604.13924"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-anomaly-detection"
  - "unsupervised-learning"
  - "transformer"
  - "llm-for-time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "latent-pseudo-anomaly-generation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T05:34:26Z"
created_at: "2026-04-18T05:34:26Z"
---

# ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection

**Authors**: Romain Hermary, Samet Hiçsönmez, Dan Pineau, Abd El Rahman Shabayek, Djamila Aouada
**Date**: 2026-04-15
**Paper ID**: [openalex:2604.13924](https://arxiv.org/abs/2604.13924)

## Summary

ASTER addresses the scarcity of labeled data in time-series anomaly detection by generating pseudo-anomalies directly within the latent space, bypassing the need for handcrafted anomaly injection. The framework utilizes a latent-space decoder combined with a pre-trained LLM to enrich temporal and contextual representations. This allows for the effective training of a Transformer-based classifier, leading to state-of-the-art performance across various benchmark datasets.

## Key Contributions

- Introduces ASTER, an unsupervised time-series anomaly detection framework that generates pseudo-anomalies in the latent space.
- Leverages a pre-trained LLM to enhance temporal and contextual representations, improving upon standard reconstruction/forecasting methods.
- Achieves state-of-the-art results on three major time-series anomaly detection benchmarks, surpassing existing embedding-based and reconstruction-based approaches.

## Open Questions & Future Work

- [[pseudo-anomaly-diversity-bottleneck]]

## Key Concepts

- [[latent-pseudo-anomaly-generation]]: A technique for unsupervised time-series anomaly detection that constructs pseudo-anomalies within the latent space, decoupling training from domain-specific hand-crafted rules.

## Archivist Review

I have approved 'Latent Pseudo-Anomaly Generation' as a core technique, focusing on the mechanism rather than the specific framework name (ASTER). I also approved a refined version of the pseudo-anomaly diversity question, as this is a tangible bottleneck for unsupervised anomaly detection. Other candidates were either too generic or effectively renamed for long-term consistency in the vault.

### Approved Concepts
- Latent Pseudo-Anomaly Generation: It addresses the bottleneck of requiring handcrafted anomalies in unsupervised time-series anomaly detection by shifting the problem to the latent space, which is a highly reusable methodology for representation learning.

### Approved Open Questions
- Latent Pseudo-Anomaly Diversity Bottleneck: The robustness of unsupervised anomaly classifiers is intrinsically linked to the coverage of the synthetic anomaly distribution; improving this is central to model performance and generalization.

### Rejected Candidates
- [concept] ASTER (Latent Pseudo-Anomaly Generation) (`aster-latent-pseudo-anomaly-generation`) - other: Renamed to 'Latent Pseudo-Anomaly Generation' to focus on the underlying methodology rather than the specific framework name.
- [open_question] Enhancing latent pseudo-anomaly diversity (`enhancing-pseudo-anomaly-diversity-in-latent-space`) - other: Renamed to follow a more concise, bottleneck-focused naming convention.
- [open_question] LLM representational performance in TSAD (`llm-representational-performance-in-time-series-ad`) - generic: The question is too broad and generic regarding the application of LLMs to time-series, lacking a specific, actionable research hurdle distinct from general foundation model adaptation.

## Links

- [Abstract](https://arxiv.org/abs/2604.13924)
- [PDF](https://arxiv.org/pdf/2604.13924)

