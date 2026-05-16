---
# CSL-compatible fields
title: "HCSG: Human-Centric Semantic-Geometric Reasoning for Vision-Language Navigation"
author:
  - literal: "Haoxuan Xu"
  - literal: "Tianfu Li"
  - literal: "Wenbo Chen"
  - literal: "Yi ran Liu"
  - literal: "Jin Wu"
  - literal: "Huashuo Lei"
  - literal: "Yunfan Lou"
  - literal: "Lujia Wang"
  - literal: "Hesheng Wang"
  - literal: "Haoang Li"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13321"

# Custom fields
paper_id: "2605.13321"
paper_source: "openalex"
domain: "nlp"
tags:
  - "vision-language-navigation"
  - "robotics"
  - "social-navigation"
  - "human-intent-prediction"
  - "dynamic-environments"
architectures:
  []
datasets:
  []
concept_slugs:
  - "hcsg-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:03:25Z"
created_at: "2026-05-16T06:03:25Z"
---

# HCSG: Human-Centric Semantic-Geometric Reasoning for Vision-Language Navigation

**Authors**: Haoxuan Xu, Tianfu Li, Wenbo Chen, Yi ran Liu, Jin Wu, Huashuo Lei, Yunfan Lou, Lujia Wang, Hesheng Wang, Haoang Li
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13321](https://arxiv.org/abs/2605.13321)

## Summary

The paper introduces HCSG, a human-centric vision-language navigation (VLN) framework designed to handle dynamic indoor environments with pedestrians. Unlike existing methods that treat humans merely as visual obstacles, HCSG employs a unified Human Understanding Module to perform explicit geometric trajectory forecasting and semantic intent interpretation using Vision-Language Models. These insights, integrated with a social distance loss, enable the navigation agent to perform instruction-conditioned planning while adhering to social norms. Experimental results on the HA-VLNCE benchmark confirm that this active reasoning approach significantly improves both navigational success and safety.

## Key Contributions

- Proposes HCSG, the first VLN framework that actively models human intentions and motion rather than treating humans as passive obstacles.
- Introduces a unified Human Understanding Module that synthesizes geometric human pose/trajectory forecasting with semantic action/intent interpretation via VLMs.
- Demonstrates a 14% improvement in Success Rate and a 34% reduction in Collision Rate on the HA-VLNCE benchmark compared to state-of-the-art methods.

## Open Questions & Future Work

- [[continuous-human-aware-streaming-navigation]]

## Key Concepts

- [[hcsg-framework]]: A human-centric vision-language navigation framework that integrates semantic intent interpretation and geometric motion forecasting for social navigation.

## Archivist Review

I have approved the HCSG framework concept due to its novel combination of VLM-driven semantic intent interpretation with traditional geometric trajectory forecasting in a navigation context. I also approved the open question regarding continuous streaming human-aware navigation, as it highlights a significant limitation in episodic RL/VLN architectures. The second open question was rejected as it is a standard research direction in social robotics that is already well-covered in existing literature.

### Approved Concepts
- HCSG Framework: Introduces a novel paradigm for VLN by combining geometric trajectory prediction with semantic action interpretation via VLMs.

### Approved Open Questions
- Continuous Human-Aware Navigation Streaming: Transitioning to a continuous streaming setting is essential for practical deployment in realistic human-populated settings, where stop-and-wait behaviors are often impractical or socially disruptive.

### Rejected Candidates
- [open_question] Adaptive Context-Aware Social Priors (`adaptive-context-aware-social-priors`) - duplicate_existing: The question of adaptive social priors is a common variation of general robotic social navigation constraints and is not sufficiently distinct from existing social-navigation research concerns.

## Links

- [Abstract](https://arxiv.org/abs/2605.13321)
- [PDF](https://arxiv.org/pdf/2605.13321)

