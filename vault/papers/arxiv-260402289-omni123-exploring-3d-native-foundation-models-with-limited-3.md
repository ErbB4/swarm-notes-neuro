---
# CSL-compatible fields
title: "Omni123: Exploring 3D Native Foundation Models with Limited 3D Data by Unifying Text to 2D and 3D Generation"
author:
  - literal: "Chongjie Ye"
  - literal: "Cheng Cao"
  - literal: "Chuanyu Pan"
  - literal: "Yiming Hao"
  - literal: "Yihao Zhi"
  - literal: "Yuanming Hu"
  - literal: "Xiaoguang Han"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02289"

# Custom fields
paper_id: "2604.02289"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "interleaved-x-to-x-training-paradigm"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:08:06Z"
created_at: "2026-04-04T20:08:06Z"
---

# Omni123: Exploring 3D Native Foundation Models with Limited 3D Data by Unifying Text to 2D and 3D Generation

**Authors**: Chongjie Ye, Cheng Cao, Chuanyu Pan, Yiming Hao, Yihao Zhi, Yuanming Hu, Xiaoguang Han
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02289](https://arxiv.org/abs/2604.02289)

## Summary

Omni123 is a 3D-native foundation model that unifies text-to-2D and text-to-3D generation within a single autoregressive framework. To address the scarcity of high-quality 3D data, the model represents text, images, and 3D assets as discrete tokens in a shared space. It utilizes an interleaved X-to-X training paradigm, traversing cross-modal cycles (text-image-3D-image) to leverage abundant 2D data as a geometric prior. This approach enforces semantic, visual, and geometric consistency, enabling improved text-guided 3D generation and editing.

## Key Contributions

- Introduces Omni123, an autoregressive foundation model that unifies text-to-2D and text-to-3D generation.
- Proposes an interleaved X-to-X training paradigm that enforces geometric consistency without requiring fully aligned text-image-3D triplets.
- Demonstrates that cross-modal cycles (text-image-3D-image) act as implicit structural constraints to improve 3D representation learning from limited 3D data.

## Key Concepts

- [[interleaved-x-to-x-training-paradigm]]: A training paradigm for multimodal foundation models that coordinates cross-modal tasks by traversing semantic-visual-geometric cycles within autoregressive sequences.

## Archivist Review

I have approved the 'Interleaved X-to-X Training Paradigm' as it presents a novel, scalable strategy for training multimodal models on sparse, non-aligned data—a significant hurdle in 3D foundation model research. No other concepts or open questions met the high threshold for permanent vault status, as the remaining aspects are specific implementation details or architecture-level choices rather than durable architectural patterns.

### Approved Concepts
- Interleaved X-to-X Training Paradigm: Enables training on heterogeneous, non-triplet data, addressing data scarcity in generative modeling for multimodal 3D.

## Links

- [Abstract](https://arxiv.org/abs/2604.02289)
- [PDF](https://arxiv.org/pdf/2604.02289)

