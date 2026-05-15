---
# CSL-compatible fields
title: "On Predicting the Post-training Potential of Pre-trained LLMs"
author:
  - literal: "Xiaoyuan Li"
  - literal: "Yubo Ma"
  - literal: "Kexin Yang"
  - literal: "Moxin Li"
  - literal: "Keqin Bao"
  - literal: "Wenie Wang"
  - literal: "Fuli Feng"
  - literal: "Dayiheng Liu"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11978"

# Custom fields
paper_id: "2605.11978"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "rude-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:16:13Z"
created_at: "2026-05-15T06:16:13Z"
---

# On Predicting the Post-training Potential of Pre-trained LLMs

**Authors**: Xiaoyuan Li, Yubo Ma, Kexin Yang, Moxin Li, Keqin Bao, Wenie Wang, Fuli Feng, Dayiheng Liu
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11978](https://arxiv.org/abs/2605.11978)

## Summary

The paper addresses the challenge of predicting the downstream task performance of base LLMs without undergoing expensive full post-training. The authors introduce the task of post-training potential prediction and propose RuDE, a framework that uses rubric-based discriminative evaluation to compare response pairs. By leveraging a systematic 4C Taxonomy of rubric violations, RuDE accurately forecasts model plasticity. Empirical results show a high correlation with post-training performance, enabling compute-efficient model selection and the identification of smaller, high-potential models.

## Key Contributions

- Introduces the post-training potential prediction task to estimate base model performance before training.
- Proposes RuDE, which utilizes response discrimination to circumvent the generation gap of base models.
- Demonstrates that RuDE achieves >90% correlation with actual post-training performance across diverse domains.
- Validates through RL that RuDE identifies high-potential smaller models that outperform larger baselines.

## Open Questions & Future Work

- [[discriminative-generative-gap-limits]]

## Key Concepts

- [[rude-framework]]: A framework for predicting a base model's post-training potential by leveraging response discrimination on contrastive pairs constructed from rubric violations.

## Archivist Review

I have approved the RuDE framework as a reusable methodological contribution for evaluating base model plasticity and the discriminative-generative gap as a significant unresolved theoretical bottleneck. I rejected no candidates because the initial submission was highly selective and focused on core contributions. The review followed the policy of prioritizing overarching frameworks over subcomponents and identifying substantial research questions rather than performance-oriented future work.

### Approved Concepts
- RuDE (Rubric-based Discriminative Evaluation): RuDE addresses the challenge of evaluating base model plasticity without performing full post-training, enabling efficient model selection.

### Approved Open Questions
- Discriminative-Generative Capability Gap: This bottleneck highlights the fundamental limitation of using discriminative proxies for generative potential, which could lead to systematic failure in model selection for creative domains.

## Links

- [Abstract](https://arxiv.org/abs/2605.11978)
- [PDF](https://arxiv.org/pdf/2605.11978)

