---
# CSL-compatible fields
title: "STLGT: A Scalable Trace-Based Linear Graph Transformer for Tail Latency Prediction in Microservices"
author:
  - literal: "Yongliang Ding"
  - literal: "Qigong Bi"
  - literal: "Peng Pu"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26422"

# Custom fields
paper_id: "2604.26422"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "DeathStarBench"
  - "Alibaba-traces"
concept_slugs:
  - "trace-based-span-graph-encoding"
dataset_slugs:
  - "deathstarbench"
  - "alibaba-traces"
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:49:41Z"
created_at: "2026-05-02T05:49:41Z"
---

# STLGT: A Scalable Trace-Based Linear Graph Transformer for Tail Latency Prediction in Microservices

**Authors**: Yongliang Ding, Qigong Bi, Peng Pu
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26422](https://arxiv.org/abs/2604.26422)

## Summary

The paper presents STLGT (Scalable Trace-based Linear Graph Transformer), a framework designed for predicting tail latency in microservice architectures. By encoding execution traces as span graphs, the model effectively captures complex cross-service dependency propagation and non-stationary, bursty workload patterns. The approach utilizes a linear graph Transformer combined with a decoupled temporal module, significantly improving both forecasting accuracy and inference efficiency compared to state-of-the-art GNN-based baselines.

## Key Contributions

- Introduces STLGT, a per-API predictor that models microservice tail-latency via span graph encoding and decoupled temporal dynamics.
- Develops a structure-aware linear graph Transformer enabling inference complexity linear to the span graph size.
- Outperforms the PERT-GNN baseline by 8.5% MAPE in p95 tail-latency forecasting and achieves 12x faster CPU inference.

## Open Questions & Future Work

- [[topology-drift-adaptation]]

## Key Concepts

- [[trace-based-span-graph-encoding]]: A structured graph-based representation of service execution traces for modeling dependency-aware latency dynamics.

## Archivist Review

The paper provides a strong technical contribution in modeling microservice latency through graph-based trace representations. I approved the span graph encoding as a reusable technique for distributed systems forecasting and the topology drift open question as a critical production bottleneck. I also added the two primary benchmark datasets used.

### Approved Concepts
- Trace-based Span Graph Encoding: This representation allows for structured modeling of heterogeneous microservice communication patterns that are often ignored by flat time-series approaches.

### Approved Open Questions
- Adaptation to Topology Drift: This is a critical bottleneck for deploying predictive auto-scaling in dynamic, production-grade cloud environments where microservice architectures evolve continuously.

### Rejected Candidates
- [concept] STLGT (`stlgt`) - subcomponent_of_broader_mechanism: This is a specific model architecture instance that is better represented by the underlying techniques (span graph encoding, linear graph transformer) rather than the acronym itself.

## Datasets

- [[deathstarbench]]
- [[alibaba-traces]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26422)
- [PDF](https://arxiv.org/pdf/2604.26422)

