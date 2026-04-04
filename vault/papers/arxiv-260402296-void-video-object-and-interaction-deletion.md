---
# CSL-compatible fields
title: "VOID: Video Object and Interaction Deletion"
author:
  - literal: "Saman Motamed"
  - literal: "William Harvey"
  - literal: "Benjamin Klein"
  - literal: "Luc Van Gool"
  - literal: "Zhuoning Yuan"
  - literal: "Ta-Ying Cheng"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02296"

# Custom fields
paper_id: "2604.02296"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "generative-models"
  - "video-processing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "void-video-object-and-interaction-deletion"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:07:54Z"
created_at: "2026-04-04T20:07:54Z"
---

# VOID: Video Object and Interaction Deletion

**Authors**: Saman Motamed, William Harvey, Benjamin Klein, Luc Van Gool, Zhuoning Yuan, Ta-Ying Cheng
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02296](https://arxiv.org/abs/2604.02296)

## Summary

VOID is a novel video object removal framework that addresses the limitation of standard inpainting models in handling complex physical interactions. By leveraging a vision-language model to identify regions impacted by the removal, the system guides a video diffusion model to generate physically consistent counterfactual outcomes. The framework is trained on a newly curated dataset generated via Kubric and HUMOTO, enabling it to better simulate the world through causal reasoning compared to appearance-only removal methods.

## Key Contributions

- Introduces VOID, a framework for physically-plausible video object removal that preserves scene dynamics post-removal.
- Proposes a data generation pipeline using Kubric and HUMOTO to create counterfactual video pairs with altered physical interactions.
- Demonstrates superior performance in maintaining physical consistency and scene dynamics compared to standard video inpainting methods on both synthetic and real-world datasets.

## Key Concepts

- [[void-video-object-and-interaction-deletion]]: A framework for physically-plausible video object removal that corrects scene dynamics affected by object-object interactions.

## Archivist Review

I approved the VOID framework as a distinct conceptual paradigm for physically-aware generative video editing, which advances beyond appearance-only inpainting. I rejected the mentioned tools (Kubric and HUMOTO) because they are simulation engines/pipelines rather than specific, novel datasets curated for evaluation. No open questions were sufficiently well-defined or generalizable beyond this study to warrant an entry.

### Approved Concepts
- VOID (Video Object and Interaction Deletion): It represents a novel paradigm in video editing that accounts for downstream physical consequences of removing objects.

### Rejected Candidates
- [dataset] Kubric (`kubric`) - other: Kubric is a general-purpose synthetic data simulation framework rather than a specific research dataset central to the paper's claims.
- [dataset] HUMOTO (`humoto`) - other: HUMOTO is an existing simulation engine or data generation tool, not a unique, reusable dataset developed for the paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.02296)
- [PDF](https://arxiv.org/pdf/2604.02296)

