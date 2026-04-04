---
# CSL-compatible fields
title: "Steerable Visual Representations"
author:
  - literal: "Jona Ruthardt"
  - literal: "Manu Gaur"
  - literal: "Deva Ramanan"
  - literal: "Makarand Tapaswi"
  - literal: "Yuki M. Asano"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02327"

# Custom fields
paper_id: "2604.02327"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "vision-language-models"
  - "representation-learning"
  - "zero-shot-learning"
architectures:
  - "Vision Transformer"
datasets:
  []
concept_slugs:
  - "steerable-visual-representations"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:07:21Z"
created_at: "2026-04-04T20:07:21Z"
---

# Steerable Visual Representations

**Authors**: Jona Ruthardt, Manu Gaur, Deva Ramanan, Makarand Tapaswi, Yuki M. Asano
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02327](https://arxiv.org/abs/2604.02327)

## Summary

This paper introduces Steerable Visual Representations, a method that enables fine-grained control over visual features using natural language prompts. By integrating lightweight cross-attention directly into the layers of a Vision Transformer (early fusion), the model allows for the guidance of visual representations toward specific concepts without sacrificing generic performance. The approach demonstrates superior zero-shot generalization and effectiveness on tasks like anomaly detection and personalized object discrimination compared to traditional vision-language models.

## Key Contributions

- Introduces Steerable Visual Representations, which integrate natural language prompts into the visual encoder via early-fusion cross-attention.
- Demonstrates that steerable features can focus on user-specified objects while maintaining high performance on general visual tasks.
- Establishes new benchmarks for evaluating representational steerability and achieves state-of-the-art results on anomaly detection and personalized object discrimination.

## Key Concepts

- [[steerable-visual-representations]]: A class of visual representations that allows global and local image features to be dynamically steered using natural language prompts.

## Archivist Review

I have approved 'Steerable Visual Representations' as a novel paradigm for vision-language alignment that moves beyond standard late-fusion approaches. I rejected 'Early Fusion Cross-Attention' as it is a supporting architectural subcomponent rather than the primary contribution itself. I followed a restrictive policy to ensure only high-level conceptual contributions enter the vault.

### Approved Concepts
- Steerable Visual Representations: It introduces a novel architecture-level paradigm (early-fusion cross-attention in ViTs) to allow textual guidance of visual feature extraction.

### Rejected Candidates
- [concept] Early Fusion Cross-Attention (`early-fusion-cross-attention`) - subcomponent_of_broader_mechanism: This is an architectural implementation detail of the primary contribution, Steerable Visual Representations.

## Links

- [Abstract](https://arxiv.org/abs/2604.02327)
- [PDF](https://arxiv.org/pdf/2604.02327)

