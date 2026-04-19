---
# CSL-compatible fields
title: "DigiForest: Digital Analytics and Robotics for Sustainable Forestry"
author:
  - literal: "Marco Camurri"
  - literal: "Enrico Tomelleri"
  - literal: "Matías Mattamala"
  - literal: "Sebastián Barbas Laina"
  - literal: "Martin Jacquet"
  - literal: "Jens Behley"
  - literal: "Sunni Kanta Prasad Kushwaha"
  - literal: "Fang Nan"
  - literal: "Nived Chebrolu"
  - literal: "Leonard Freißmuth"
  - literal: "Marvin Chayton Harms"
  - literal: "Meher V. R. Malladi"
  - literal: "Fan Yang"
  - literal: "Jonas Frey"
  - literal: "Cesar Cadena"
  - literal: "Marco Hutter"
  - literal: "Janine Schweier"
  - literal: "Kostas Alexis"
  - literal: "Cyrill Stachniss"
  - literal: "Maurice Fallon"
  - literal: "Stefan Leutenegger"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14652"

# Custom fields
paper_id: "2604.14652"
paper_source: "openalex"
domain: "time-series"
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
processed_at: "2026-04-19T05:45:32Z"
created_at: "2026-04-19T05:45:32Z"
---

# DigiForest: Digital Analytics and Robotics for Sustainable Forestry

**Authors**: Marco Camurri, Enrico Tomelleri, Matías Mattamala, Sebastián Barbas Laina, Martin Jacquet, Jens Behley, Sunni Kanta Prasad Kushwaha, Fang Nan, Nived Chebrolu, Leonard Freißmuth, Marvin Chayton Harms, Meher V. R. Malladi, Fan Yang, Jonas Frey, Cesar Cadena, Marco Hutter, Janine Schweier, Kostas Alexis, Cyrill Stachniss, Maurice Fallon, Stefan Leutenegger
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.14652](https://arxiv.org/abs/2604.14652)

## Summary

DigiForest is a comprehensive precision forestry framework that integrates autonomous aerial, legged, and marsupial robotics to facilitate high-resolution forest monitoring and data collection. The system automates the extraction of forest inventory traits and employs a Decision Support System (DSS) to model forest growth and guide sustainable management practices. By incorporating purpose-built autonomous harvesters for low-impact logging, the project provides an end-to-end solution for large-scale, sustainable forest ecosystem management. The approach has been extensively validated across various European forest types, demonstrating the feasibility of autonomous robotics for long-term ecological monitoring and industrial forestry.

## Key Contributions

- Introduces DigiForest, an integrated framework for precision forestry combining heterogeneous autonomous robotics with digital forest analytics.
- Develops automated pipelines for high-fidelity, tree-level trait extraction and inventory management.
- Implements a Decision Support System (DSS) for forest growth forecasting and sustainable management decision-making.
- Validates the end-to-end approach through real-world deployments in diverse forest environments including Finland, the UK, and Switzerland.

## Open Questions & Future Work

- [[real-time-forest-panoptic-segmentation]]

## Archivist Review

I have reviewed the proposal and approved one open question concerning real-time panoptic segmentation, as this represents a fundamental algorithmic challenge for autonomous agents in unstructured environments. Other candidates were rejected for being overly specialized to specific robot architectures or implementation details rather than representing broad scientific bottlenecks. The concepts were not selected as the framework provided is a broad system architecture rather than a novel, reusable modeling concept.

### Approved Open Questions
- Real-time Forest Panoptic Segmentation: Real-time on-board semantic scene understanding is a critical bottleneck for fully autonomous forestry operations, as it enables robots to make informed, immediate decisions based on the structural properties of the forest environment.

### Rejected Candidates
- [open_question] Marsupial Robot Coordination in Forestry (`marsupial-robot-coordination-forestry`) - low_impact: The problem is highly specific to a niche robotics configuration rather than a fundamental theoretical or algorithmic bottleneck in forestry analytics.

## Links

- [Abstract](https://arxiv.org/abs/2604.14652)
- [PDF](https://arxiv.org/pdf/2604.14652)

