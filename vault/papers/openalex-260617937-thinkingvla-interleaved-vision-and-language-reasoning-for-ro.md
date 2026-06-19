---
# CSL-compatible fields
title: "ThinkingVLA: Interleaved Vision and Language Reasoning for Robotic Manipulation"
author:
  - literal: "Tianyi Lu"
  - literal: "Hui Zhang"
  - literal: "Zijie Diao"
  - literal: "Junke Wang"
  - literal: "Shengqi Xu"
  - literal: "Xingyao Lin"
  - literal: "Guojin Zhong"
  - literal: "Z Zhenyu Ye"
  - literal: "Peng Wang"
  - literal: "Zuxuan Wu"
  - literal: "Yi Jiang"
issued:
  date-parts:
    - [2026, 6, 16]
url: "https://arxiv.org/abs/2606.17937"

# Custom fields
paper_id: "2606.17937"
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
processed_at: "2026-06-19T06:48:05Z"
created_at: "2026-06-19T06:48:05Z"
---

# ThinkingVLA: Interleaved Vision and Language Reasoning for Robotic Manipulation

**Authors**: Tianyi Lu, Hui Zhang, Zijie Diao, Junke Wang, Shengqi Xu, Xingyao Lin, Guojin Zhong, Z Zhenyu Ye, Peng Wang, Zuxuan Wu, Yi Jiang
**Date**: 2026-06-16
**Paper ID**: [openalex:2606.17937](https://arxiv.org/abs/2606.17937)

## Summary

ThinkingVLA addresses the limitation of standard VLA models that map inputs to actions without explicit reasoning by introducing a unified autoregressive architecture that integrates textual and visual reasoning. The framework decomposes robotic manipulation into a forward CoT for subgoal identification and visual state prediction, followed by an inverse CoT that infers necessary actions based on the predicted target state. By interleaving these processes, ThinkingVLA achieves superior reasoning capacity for long-horizon manipulation tasks compared to non-reasoning or monolithic VLA baselines.

## Key Contributions

- Introduces ThinkingVLA, a unified generative model that interleaves textual and visual reasoning for robotic manipulation.
- Implements a novel forward-and-inverse Chain-of-Thought (CoT) mechanism that performs subgoal decomposition followed by state-conditioned inverse action prediction.
- Demonstrates significant performance gains over existing VLA models on long-horizon manipulation tasks in both simulation and real-world environments.

## Links

- [Abstract](https://arxiv.org/abs/2606.17937)
- [PDF](https://arxiv.org/pdf/2606.17937)

