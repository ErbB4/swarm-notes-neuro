---
# CSL-compatible fields
title: "ProPACT: A Proactive AI-Driven Adaptive Collaborative Tutor for Pair Programming"
author:
  - literal: "Anahita Golrang"
  - literal: "Kshitij Sharma"
  - literal: "olga viberg"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02703"

# Custom fields
paper_id: "2605.02703"
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
processed_at: "2026-05-07T06:04:29Z"
created_at: "2026-05-07T06:04:29Z"
---

# ProPACT: A Proactive AI-Driven Adaptive Collaborative Tutor for Pair Programming

**Authors**: Anahita Golrang, Kshitij Sharma, olga viberg
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02703](https://arxiv.org/abs/2605.02703)

## Summary

ProPACT is an AI-driven adaptive tutor designed to support collaborative pair programming by treating the dyadic interaction as the primary object of instruction. The system constructs a multimodal learner model incorporating Joint Visual Attention and Joint Mental Effort to forecast suboptimal collaboration states using an XGBoost-based predictive model. These real-time predictions trigger a hierarchical policy that provides minimally intrusive scaffolds, effectively enhancing task performance and collaboration quality during debugging activities.

## Key Contributions

- Introduces ProPACT, a proactive AI tutor that predicts suboptimal collaboration states in pair programming up to 30 seconds in advance.
- Implements a multimodal dyadic learner model utilizing Joint Visual Attention (JVA) and Joint Mental Effort (JME) as input features for adaptive scaffolding.
- Demonstrates through a within-subject study of 26 dyads that proactive, forecast-driven feedback significantly improves debugging outcomes and joint regulation efficacy.

## Open Questions & Future Work

- [[scalable-multimodal-signals-for-collaboration]]
- [[longitudinal-impact-of-scaffolding]]

## Archivist Review

The paper presents a domain-specific application of forecasting for adaptive collaborative learning. I found the proposed concepts too application-specific or standard (e.g., XGBoost, hierarchical policies) to merit new permanent conceptual notes. However, the open questions regarding the scalability of collaborative sensing hardware and the longitudinal effects of scaffolded learning are substantial, research-critical bottlenecks that deserve tracking in the vault.

### Approved Open Questions
- Scaling Multimodal Collaborative Sensing: High; the reliance on specialized, expensive hardware is a major bottleneck preventing the widespread adoption of AI-driven collaborative tutoring systems.
- Longitudinal Impact of Scaffolding: Medium; understanding the long-term impact is critical for ensuring that AI tutors promote sustainable learning outcomes rather than creating dependency.

## Links

- [Abstract](https://arxiv.org/abs/2605.02703)
- [PDF](https://arxiv.org/pdf/2605.02703)

