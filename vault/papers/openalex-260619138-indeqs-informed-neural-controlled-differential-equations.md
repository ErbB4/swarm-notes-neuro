---
# CSL-compatible fields
title: "INDEQS: Informed Neural controlled Differential EQuationS"
author:
  - literal: "Michael Detzel"
  - literal: "Gabriel Nobis"
  - literal: "Kristiyan Blagov"
  - literal: "Juri Schubert"
  - literal: "J Y"
  - literal: "Wojciech Samek"
issued:
  date-parts:
    - [2026, 6, 17]
url: "https://arxiv.org/abs/2606.19138"

# Custom fields
paper_id: "2606.19138"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "neural-differential-equations"
  - "spatio-temporal-forecasting"
  - "physics-informed-learning"
architectures:
  []
datasets:
  - "pems08"
concept_slugs:
  - "indeqs-framework"
dataset_slugs:
  - "pems08"
skill: "TimeSeriesSkill"
processed_at: "2026-06-20T06:32:56Z"
created_at: "2026-06-20T06:32:56Z"
---

# INDEQS: Informed Neural controlled Differential EQuationS

**Authors**: Michael Detzel, Gabriel Nobis, Kristiyan Blagov, Juri Schubert, J Y, Wojciech Samek
**Date**: 2026-06-17
**Paper ID**: [openalex:2606.19138](https://arxiv.org/abs/2606.19138)

## Summary

INDEQS is a graph-based Neural Controlled Differential Equation (NCDE) framework designed to integrate prior knowledge of directed graph structures into continuous-time time series forecasting. The method separates inner state mixing across graph nodes from outer mixing between the vector field and control, allowing for more structured and parameter-efficient learning. Evaluated on synthetic advection simulations and real-world river discharge and traffic flow (PeMS08) data, INDEQS consistently outperforms standard uninformed NCDEs, particularly when graph informedness is applied to the outer mixing components.

## Key Contributions

- Introduces INDEQS, a framework that incorporates known directed graph structures into NCDEs by separating inner and outer state mixing.
- Proposes two variants: a lightweight graph-constrained approach and an expressive variant with adaptive graph convolutions.
- Demonstrates superior forecasting performance on river discharge networks and the PeMS08 traffic dataset compared to uninformed NCDE baselines.

## Key Concepts

- [[indeqs-framework]]: A graph-based Neural Controlled Differential Equation framework that injects prior directed graph knowledge through the architectural separation of inner state mixing and outer control-vector field mixing.

## Archivist Review

The paper introduces a structured way to incorporate prior knowledge into neural controlled differential equations. I have approved the framework as it proposes a specific, reusable architectural design (separating inner/outer mixing) for continuous-time spatio-temporal modeling. PeMS08 is approved as a representative dataset for traffic flow prediction.

### Approved Concepts
- Informed Neural Controlled Differential Equations (INDEQS): It defines a systematic methodology for injecting known relational structure into neural differential equations by bifurcating the integration of graph connectivity from the vector field-control interaction.

### Rejected Candidates
- [concept] INDEQS (`indeqs`) - other: Renamed for better descriptive clarity and consistency with established naming patterns in the vault.

## Datasets

- [[pems08]]

## Links

- [Abstract](https://arxiv.org/abs/2606.19138)
- [PDF](https://arxiv.org/pdf/2606.19138)

