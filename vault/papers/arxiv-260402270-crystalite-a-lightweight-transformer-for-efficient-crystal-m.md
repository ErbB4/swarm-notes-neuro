---
# CSL-compatible fields
title: "Crystalite: A Lightweight Transformer for Efficient Crystal Modeling"
author:
  - literal: "Tin Hadži Veljković"
  - literal: "Joshua Rosenthal"
  - literal: "Ivor Lončarić"
  - literal: "Jan-Willem van de Meent"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02270"

# Custom fields
paper_id: "2604.02270"
paper_source: "arxiv"
domain: "materials-science-machine-learning"
tags:
  - "diffusion-models"
  - "transformers"
  - "materials-science"
  - "generative-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "subatomic-tokenization"
  - "geometry-enhancement-module"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:08:26Z"
created_at: "2026-04-04T20:08:26Z"
---

# Crystalite: A Lightweight Transformer for Efficient Crystal Modeling

**Authors**: Tin Hadži Veljković, Joshua Rosenthal, Ivor Lončarić, Jan-Willem van de Meent
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02270](https://arxiv.org/abs/2604.02270)

## Summary

Crystalite is a lightweight diffusion Transformer designed for efficient crystalline material modeling. By utilizing Subatomic Tokenization and a Geometry Enhancement Module (GEM), it incorporates necessary chemical and spatial inductive biases without the computational overhead typical of equivariant graph neural networks. The model achieves state-of-the-art results on crystal structure prediction and de novo generation while offering faster sampling speeds than existing geometry-focused alternatives.

## Key Contributions

- Introduces Crystalite, a diffusion-based Transformer optimized for efficiency in crystal modeling.
- Develops Subatomic Tokenization to replace one-hot atom encodings with a chemically structured representation suitable for continuous diffusion.
- Proposes the Geometry Enhancement Module (GEM) to inject periodic geometry into standard attention mechanisms via additive biases.
- Achieves state-of-the-art S.U.N. discovery scores while significantly reducing sampling latency compared to equivariant GNN baselines.

## Key Concepts

- [[subatomic-tokenization]]: A compact, chemically structured atom representation that replaces one-hot encodings to better support continuous diffusion in crystalline materials.
- [[geometry-enhancement-module]]: An attention-based module that integrates periodic geometric constraints into Transformers using additive biases.

## Archivist Review

The paper introduces two architectural innovations for efficient crystal modeling. I have approved 'Subatomic Tokenization' and 'Geometry Enhancement Module' as they represent reusable techniques for adapting standard Transformers to structured physical domains, consistent with the goal of identifying durable ML mechanisms. No datasets or open questions were approved as none met the strict criteria for standalone vault entries.

### Approved Concepts
- Subatomic Tokenization: It enables more efficient and effective diffusion-based modeling of atomic systems by replacing high-dimensional, discrete encodings with continuous, chemically aware representations.
- Geometry Enhancement Module: It provides a lightweight mechanism to incorporate complex periodic spatial dependencies into standard attention mechanisms without needing expensive equivariant graph neural network architectures.

## Links

- [Abstract](https://arxiv.org/abs/2604.02270)
- [PDF](https://arxiv.org/pdf/2604.02270)

