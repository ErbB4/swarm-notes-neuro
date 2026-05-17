---
# CSL-compatible fields
title: "Sub-Band Full Duplex Resource Allocation: A Predictive Deep Reinforcement Learning Approach"
author:
  - literal: "Abhiram D"
  - literal: "Aiswarya Rajan"
  - literal: "Arin Shemeem"
  - literal: "Vipindev Adat Vasudevan"
  - literal: "Abdulla P"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14339"

# Custom fields
paper_id: "2605.14339"
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
processed_at: "2026-05-17T06:08:37Z"
created_at: "2026-05-17T06:08:37Z"
---

# Sub-Band Full Duplex Resource Allocation: A Predictive Deep Reinforcement Learning Approach

**Authors**: Abhiram D, Aiswarya Rajan, Arin Shemeem, Vipindev Adat Vasudevan, Abdulla P
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.14339](https://arxiv.org/abs/2605.14339)

## Summary

This paper proposes a predictive resource allocation framework for Sub-Band Full Duplex (SBFD) systems by combining traffic forecasting with deep reinforcement learning. A Bi-LSTM model predicts bursty traffic patterns, which, along with real-time queue states, informs a Double Deep Q-Network (DDQN) agent that dynamically optimizes UL/DL split ratios. The framework demonstrates significant improvements in spectrum utilization and system adaptability over static configuration methods, offering a scalable solution for 6G network management.

## Key Contributions

- Introduces a hybrid Bi-LSTM and DDQN framework for dynamic sub-band allocation in SBFD systems.
- Achieves proactive resource management by integrating traffic forecasts with queue state information for real-time UL/DL split ratio adaptation.
- Demonstrates improved spectrum efficiency and reduced queue latency compared to static resource allocation configurations.

## Open Questions & Future Work

- [[multi-agent-sbfd-resource-allocation-bottleneck]]

## Archivist Review

The proposed framework combines standard architectures (Bi-LSTM, DDQN) for a specific network optimization task (SBFD allocation). These are well-established techniques rather than novel conceptual contributions. The open question regarding multi-agent scalability is approved as it addresses a fundamental limitation in applying this class of RL-based resource management to realistic, multi-cell telecommunication environments.

### Approved Open Questions
- Multi-Agent SBFD Resource Allocation: Current SBFD research often focuses on simplified, single-cell environments, yet scaling to realistic, multi-cell networks is a critical barrier for practical RAN deployment where inter-cell coordination is necessary.

### Rejected Candidates
- [open_question] Multi-Agent SBFD Resource Allocation (`multi-agent-sbfd-resource-allocation`) - other: Renamed to include -bottleneck suffix to match existing vault taxonomy for research limitations.

## Links

- [Abstract](https://arxiv.org/abs/2605.14339)
- [PDF](https://arxiv.org/pdf/2605.14339)

