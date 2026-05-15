---
# CSL-compatible fields
title: "Pretraining Strategies and Scaling for ECG Foundation Models: A Systematic Study"
author:
  - literal: "M A Al-Masud"
  - literal: "Nils Strodthoff"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12241"

# Custom fields
paper_id: "2605.12241"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:16:19Z"
created_at: "2026-05-15T06:16:19Z"
---

# Pretraining Strategies and Scaling for ECG Foundation Models: A Systematic Study

**Authors**: M A Al-Masud, Nils Strodthoff
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12241](https://arxiv.org/abs/2605.12241)

## Summary

This paper provides a systematic, large-scale investigation into pretraining strategies for electrocardiography (ECG) foundation models. By evaluating five self-supervised learning objectives and scaling data up to 11M samples, the authors identify contrastive predictive coding as a leading method for generating transferable clinical representations. Crucially, the study reveals that structured state space models outperform traditional transformers and CNNs, suggesting that domain-specific inductive biases are more critical than scale alone for physiological time series analysis.

## Key Contributions

- Evaluates five self-supervised learning objectives for ECG foundation models, finding contrastive predictive coding (CPC) most effective.
- Demonstrates continued performance improvements for ECG representation learning when scaling pretraining data up to 11M samples.
- Identifies structured state space models as superior to transformer and CNN architectures for clinical ECG signal tasks.

## Open Questions & Future Work

- [[architectural-vs-scale-dominance-in-physiological-fms]]

## Archivist Review

The paper provides a rigorous comparative study of ECG representation learning. I approved a refined open question that specifically addresses the tension between architectural inductive biases (like SSMs) and scaling, which is a major ongoing discussion in time-series foundation models. No concepts were approved as the methods mentioned (CPC, JEPA, SSMs) are already established field-wide rather than contributions unique to this study.

### Approved Open Questions
- Architectural vs. Scale Dominance in Physiological FMs: This is a foundational concern for the field of physiological time-series modeling, as it directly impacts the design and scalability of future clinical AI tools. Identifying the limits of architectural superiority and the role of multimodal supervision is essential for moving beyond purely self-supervised ECG foundation models.

### Rejected Candidates
- [open_question] Future directions for ECG FMs (`future-of-ecg-foundation-models`) - generic: The candidate title and scope were overly generic and essentially summarized the paper rather than focusing on a specific technical bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.12241)
- [PDF](https://arxiv.org/pdf/2605.12241)

