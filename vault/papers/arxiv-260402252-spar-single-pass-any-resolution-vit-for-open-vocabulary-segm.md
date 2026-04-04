---
# CSL-compatible fields
title: "SPAR: Single-Pass Any-Resolution ViT for Open-vocabulary Segmentation"
author:
  - literal: "Naomi Kombol"
  - literal: "Ivan Martinović"
  - literal: "Siniša Šegvić"
  - literal: "Giorgos Tolias"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02252"

# Custom fields
paper_id: "2604.02252"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "vision-transformers"
  - "segmentation"
  - "knowledge-distillation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spar-single-pass-any-resolution-vit"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:08:33Z"
created_at: "2026-04-04T20:08:33Z"
---

# SPAR: Single-Pass Any-Resolution ViT for Open-vocabulary Segmentation

**Authors**: Naomi Kombol, Ivan Martinović, Siniša Šegvić, Giorgos Tolias
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02252](https://arxiv.org/abs/2604.02252)

## Summary

SPAR addresses the high computational cost of sliding-window inference in ViT-based open-vocabulary segmentation by enabling resolution-agnostic single-pass feature extraction. The method distills high-resolution spatial reasoning capabilities from a fine-strided teacher into a student network using a feature regression loss, eliminating the need for architectural modifications or pixel-level annotations. Experimental results demonstrate that SPAR significantly enhances segmentation performance and efficiency, effectively bridging the gap between coarse patch-level representations and the need for dense pixel-level reasoning.

## Key Contributions

- Introduces SPAR, a resolution-agnostic ViT feature extraction framework that enables efficient high-resolution inference via single-pass processing.
- Utilizes a feature regression distillation objective to transfer knowledge from a high-cost sliding-window teacher to a single-pass student without needing pixel-level supervision.
- Achieves a gain of up to 10.5 mIoU over standard single-pass baselines in open-vocabulary segmentation while simultaneously improving computational efficiency.

## Key Concepts

- [[spar-single-pass-any-resolution-vit]]: A resolution-agnostic dense feature extractor that distills sliding-window teacher features into a single-pass student ViT.

## Archivist Review

I have approved the 'SPAR' framework as a central contribution. It offers a generalizable technique for resolution-agnostic inference in Vision Transformers, which addresses a significant efficiency bottleneck in vision-language tasks. No other candidates were proposed, and I have maintained a selective stance by only approving this primary conceptual contribution.

### Approved Concepts
- SPAR (Single-Pass Any-Resolution ViT): It proposes a novel distillation framework for resolution-agnostic feature extraction in vision-language models, bypassing expensive sliding-window inference.

## Links

- [Abstract](https://arxiv.org/abs/2604.02252)
- [PDF](https://arxiv.org/pdf/2604.02252)

