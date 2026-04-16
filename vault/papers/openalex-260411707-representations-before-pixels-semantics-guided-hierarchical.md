---
# CSL-compatible fields
title: "Representations Before Pixels: Semantics-Guided Hierarchical Video Prediction"
author:
  - literal: "Efstathios Karypidis"
  - literal: "Spyros Gidaris"
  - literal: "Nikos Komodakis"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11707"

# Custom fields
paper_id: "2604.11707"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "generative-models"
  - "video-prediction"
  - "diffusion-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "semantic-representation-prediction-video-synthesis"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:47:06Z"
created_at: "2026-04-16T05:47:06Z"
---

# Representations Before Pixels: Semantics-Guided Hierarchical Video Prediction

**Authors**: Efstathios Karypidis, Spyros Gidaris, Nikos Komodakis
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11707](https://arxiv.org/abs/2604.11707)

## Summary

Re2Pix is a hierarchical video prediction framework that addresses the trade-off between semantic consistency and visual fidelity by decomposing the forecasting process. Instead of predicting pixels directly, the model first forecasts future scene dynamics within the feature space of a pre-trained foundation model and subsequently uses these representations to condition a latent diffusion model for frame synthesis. To overcome the accumulation of errors in autoregressive prediction, the authors introduce nested dropout and mixed supervision techniques. Experiments on autonomous driving benchmarks show that this semantics-first approach significantly enhances both perceptual quality and temporal coherence.

## Key Contributions

- Introduces Re2Pix, a hierarchical prediction framework that decouples semantic feature forecasting from latent diffusion-based pixel synthesis.
- Proposes nested dropout and mixed supervision strategies to mitigate the train-test distribution shift inherent in autoregressive representation prediction.
- Demonstrates improved temporal semantic consistency and visual fidelity on autonomous driving benchmarks compared to standard diffusion-based video prediction baselines.

## Open Questions & Future Work

- [[hierarchical-forecasting-distribution-shift]]

## Key Concepts

- [[semantic-representation-prediction-video-synthesis]]: A hierarchical generative paradigm that separates the forecasting of semantic feature representations from subsequent pixel-level synthesis.

## Archivist Review

The concept of decoupled hierarchical prediction for video generation was approved as a core contribution to the field of generative models. The open question was reframed to focus on the fundamental challenge of train-test mismatch in multi-stage generation, which is a known, significant bottleneck in such architectures. Other candidates were rejected for being overly model-specific (Re2Pix) or generic application-level extensions (controllability).

### Approved Concepts
- Semantic Representation Prediction for Video Synthesis: The paper formalizes a decoupled hierarchical paradigm that is likely to become a standard pattern in generative video modeling, distinct from monolithic frame-to-frame approaches.

### Approved Open Questions
- Hierarchical Forecasting Distribution Shift: Addressing the error accumulation and distributional mismatch between stages is critical for the practical viability of multi-stage generative models.

### Rejected Candidates
- [concept] Re2Pix (`re2pix`) - subcomponent_of_broader_mechanism: This is a specific model architecture name; the underlying technique (hierarchical decoupled forecasting) is the more reusable and significant concept.
- [open_question] Expanding VFM Feature Guidance Diversity (`expand-vfm-feature-guidance-diversity`) - low_impact: This is framed more as a set of incremental experiments (using different models) rather than a fundamental theoretical bottleneck.
- [open_question] Integrating Controllability in Hierarchical Generation (`integrating-controllability-in-hierarchical-generation`) - generic: Controllability is a general generative modeling challenge; the candidate does not define a specific, novel technical bottleneck unique to hierarchical video architectures.

## Links

- [Abstract](https://arxiv.org/abs/2604.11707)
- [PDF](https://arxiv.org/pdf/2604.11707)

