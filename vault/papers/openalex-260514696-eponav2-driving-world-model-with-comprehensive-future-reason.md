---
# CSL-compatible fields
title: "EponaV2: Driving World Model with Comprehensive Future Reasoning"
author:
  - literal: "Jiawei Xu"
  - literal: "Zhizhou Zhong"
  - literal: "Zhijian Shu"
  - literal: "Mingkai Jia"
  - literal: "Mingxiao Li"
  - literal: "Jia-Wang Bian"
  - literal: "Qian Zhang"
  - literal: "Kaicheng Zhang"
  - literal: "Jin Xie"
  - literal: "Jian Yang"
  - literal: "Wei Yin"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14696"

# Custom fields
paper_id: "2605.14696"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "autonomous-driving"
  - "world-models"
  - "trajectory-planning"
  - "flow-matching"
  - "representation-learning"
architectures:
  []
datasets:
  - "NAVSIM"
concept_slugs:
  - "flow-matching-group-relative-policy-optimization"
dataset_slugs:
  - "navsim"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:08:20Z"
created_at: "2026-05-17T06:08:20Z"
---

# EponaV2: Driving World Model with Comprehensive Future Reasoning

**Authors**: Jiawei Xu, Zhizhou Zhong, Zhijian Shu, Mingkai Jia, Mingxiao Li, Jia-Wang Bian, Qian Zhang, Kaicheng Zhang, Jin Xie, Jian Yang, Wei Yin
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14696](https://arxiv.org/abs/2605.14696)

## Summary

EponaV2 is a perception-free driving world model that addresses the limitations of next-frame image forecasting by incorporating multi-modal future reasoning, including 3D geometry and semantic maps. By shifting from simple image prediction to comprehensive scene forecasting, the model achieves better environmental understanding and more robust trajectory planning. Furthermore, it incorporates a flow matching group relative policy optimization mechanism to align generative outputs with planning goals, achieving significant performance gains on the NAVSIM benchmark suite.

## Key Contributions

- Introduces EponaV2, a perception-free driving world model that enhances trajectory planning via comprehensive future geometric and semantic representation forecasting.
- Implements a flow matching group relative policy optimization mechanism to refine planning accuracy, borrowing training strategies from LLMs.
- Achieves state-of-the-art results on three NAVSIM benchmarks, improving over existing perception-free models by +1.3 PDMS and +5.5 EPDMS.

## Open Questions & Future Work

- [[pseudo-label-precision-bottleneck-in-driving-world-models]]

## Key Concepts

- [[flow-matching-group-relative-policy-optimization]]: A policy optimization training mechanism for generative driving world models that aligns forecasted scene representations with trajectory planning objectives.

## Archivist Review

Approved the core policy optimization mechanism for alignment in driving world models and the NAVSIM benchmark, which is central to the evaluation claims. The open question was renamed for better alignment with existing vault naming conventions, focusing on the bottleneck of using pseudo-labels in self-supervised driving architectures.

### Approved Concepts
- Flow Matching Group Relative Policy Optimization: This mechanism acts as a novel training recipe inspired by LLMs specifically for improving trajectory planning in driving world models.

### Approved Open Questions
- Pseudo-label Precision in Driving: This bottleneck directly limits the scalability and real-world applicability of perception-free driving world models, which are otherwise highly desirable for bypassing expensive manual data labeling.

## Datasets

- [[navsim]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14696)
- [PDF](https://arxiv.org/pdf/2605.14696)

