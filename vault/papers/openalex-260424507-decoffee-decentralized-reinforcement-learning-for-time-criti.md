---
# CSL-compatible fields
title: "DECOFFEE: Decentralized Reinforcement Learning for Time-critical Workload Offloading and Energy Efficiency across the Computing Continuum"
author:
  - literal: "Anastasios Giannopoulos"
  - literal: "Sotirios Spantideas"
  - literal: "Panagiotis Trakadas"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24507"

# Custom fields
paper_id: "2604.24507"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "decoffee"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:05:33Z"
created_at: "2026-04-30T06:05:33Z"
---

# DECOFFEE: Decentralized Reinforcement Learning for Time-critical Workload Offloading and Energy Efficiency across the Computing Continuum

**Authors**: Anastasios Giannopoulos, Sotirios Spantideas, Panagiotis Trakadas
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24507](https://arxiv.org/abs/2604.24507)

## Summary

The paper presents DECOFFEE, a decentralized multi-agent reinforcement learning framework for optimizing time-critical workload offloading across the edge-cloud continuum. By modeling the offloading process as parallel Markov Decision Processes, the framework uses a Double Dueling DQN architecture integrated with LSTM forecasting to make adaptive placement decisions based on local state observations and network predictions. Simulations show that the approach effectively minimizes energy consumption and latency while reducing workload drop rates compared to conventional heuristic baselines.

## Key Contributions

- Introduces DECOFFEE, a multi-agent reinforcement learning framework that optimizes workload placement across the edge-cloud continuum.
- Utilizes a Double Dueling Deep Q-Network combined with LSTM-based forecasting to manage stochastic workload arrivals and time-varying network conditions.
- Achieves superior performance over standard heuristic and rule-based offloading strategies regarding system delay, energy consumption, and workload drop rates.

## Open Questions & Future Work

- [[federated-learning-for-decentralized-drl]]

## Key Concepts

- [[decoffee]]: A decentralized multi-agent reinforcement learning framework designed to optimize workload offloading, energy efficiency, and latency in edge-cloud computing environments.

## Archivist Review

I approved the DECOFFEE framework as a representative approach for decentralized workload orchestration in edge-cloud systems. I also approved an open question regarding the integration of federated learning into such decentralized RL schemes, as this addresses a common scalability and privacy bottleneck in distributed computing architectures. I rejected no other candidates as only one of each category was proposed.

### Approved Concepts
- DECOFFEE: This is the primary framework proposed in the paper, defining a multi-agent approach for workload offloading in edge-cloud systems.

### Approved Open Questions
- Federated Learning for Decentralized DRL: This is a critical bottleneck for scaling multi-agent DRL in large-scale distributed edge environments where privacy concerns or communication overhead prevent centralized model training or raw data exchange.

## Links

- [Abstract](https://arxiv.org/abs/2604.24507)
- [PDF](https://arxiv.org/pdf/2604.24507)

