---
# CSL-compatible fields
title: "Unifying Group-Relative and Self-Distillation Policy Optimization via Sample Routing"
author:
  - literal: "Gengsheng Li"
  - literal: "Tianyu Yang"
  - literal: "Junfeng Fang"
  - literal: "Mingyang Song"
  - literal: "Mao Zheng"
  - literal: "Haiyun Guo"
  - literal: "Dan Zhang"
  - literal: "Jinqiao Wang"
  - literal: "Tat-Seng Chua"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02288"

# Custom fields
paper_id: "2604.02288"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "sample-routed-policy-optimization"
dataset_slugs:
  []
skill: "NLPSkill"
processed_at: "2026-04-04T20:08:12Z"
created_at: "2026-04-04T20:08:12Z"
---

# Unifying Group-Relative and Self-Distillation Policy Optimization via Sample Routing

**Authors**: Gengsheng Li, Tianyu Yang, Junfeng Fang, Mingyang Song, Mao Zheng, Haiyun Guo, Dan Zhang, Jinqiao Wang, Tat-Seng Chua
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02288](https://arxiv.org/abs/2604.02288)

## Summary

The paper addresses the trade-off between the stability of Group Relative Policy Optimization (GRPO) and the rapid convergence of Self-Distillation Policy Optimization (SDPO) in RLVR for LLMs. The authors identify that SDPO suffers from training collapse due to signal degradation on correct samples and unreliable distillation targets. To bridge these paradigms, they introduce Sample-Routed Policy Optimization (SRPO), which uses a routing mechanism to apply reward-based reinforcement to correct samples and logit-based correction to failed ones, further refined by an entropy-aware weighting strategy. Experimental results demonstrate that SRPO achieves higher peak performance and better long-horizon stability than either constituent method while lowering per-step compute costs.

## Key Contributions

- Proposes SRPO, a unified policy optimization framework that dynamically routes rollouts between GRPO and SDPO based on performance success.
- Introduces an entropy-aware dynamic weighting mechanism to stabilize self-distillation by filtering unreliable targets.
- Achieves superior performance on five benchmarks, with a 3.4% average improvement over GRPO and 6.3% over SDPO on Qwen3-8B, while reducing compute costs.

## Key Concepts

- [[sample-routed-policy-optimization]]: A unified reinforcement learning framework that selectively applies reward-aligned reinforcement or logit-level distillation based on sample correctness.

## Archivist Review

The approval process focused on identifying the core methodological innovation of the paper. Sample-Routed Policy Optimization (SRPO) is approved as a distinct and reusable framework for policy optimization that bridges two prominent RLVR paradigms. Other potential candidates were deemed either subordinate to the main methodology or lacking sufficient distinctness as standalone concepts.

### Approved Concepts
- Sample-Routed Policy Optimization (SRPO): It is the core methodological contribution of the paper, offering a novel hybrid approach to policy optimization that combines group-relative and self-distillation methods.

## Links

- [Abstract](https://arxiv.org/abs/2604.02288)
- [PDF](https://arxiv.org/pdf/2604.02288)

