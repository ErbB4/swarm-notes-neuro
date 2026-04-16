---
# CSL-compatible fields
title: "Towards Situation-aware State Modeling for Air Traffic Flow Prediction"
author:
  - literal: "Anqi Liu"
  - literal: "Bin Wang"
  - literal: "Jigang Zhao"
  - literal: "Dechuan Ma"
  - literal: "Guiyuan Jiang"
  - literal: "Feng Hong"
  - literal: "Yanwei Yu"
  - literal: "Tianrui Li"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11198"

# Custom fields
paper_id: "2604.11198"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "state-to-flow-modeling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:46Z"
created_at: "2026-04-16T05:46:46Z"
---

# Towards Situation-aware State Modeling for Air Traffic Flow Prediction

**Authors**: Anqi Liu, Bin Wang, Jigang Zhao, Dechuan Ma, Guiyuan Jiang, Feng Hong, Yanwei Yu, Tianrui Li
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11198](https://arxiv.org/abs/2604.11198)

## Summary

The paper proposes AeroSense, a novel framework for air traffic flow prediction in terminal airspace that moves away from traditional aggregated time series forecasting. By modeling the airspace as a dynamic set of microscopic aircraft states, the approach effectively captures real-time kinematics and inter-aircraft interactions. Using a masked self-attention architecture with decoupled prediction heads, the model achieves state-of-the-art predictive performance on a large-scale real-world airport dataset. The results demonstrate superior robustness and interpretability compared to standard time-series paradigms.

## Key Contributions

- Introduces AeroSense, a direct state-to-flow modeling framework that processes microscopic aircraft states as a dynamic set instead of aggregate time series.
- Develops a situation-aware state representation to capture real-time terminal airspace dynamics.
- Outperforms traditional time series-based baselines on a large-scale real-world airport dataset, particularly during peak traffic periods.

## Open Questions & Future Work

- [[scalability-set-based-air-traffic-forecasting]]

## Key Concepts

- [[state-to-flow-modeling]]: A modeling paradigm that represents complex systems as a dynamic set of microscopic states and maps them directly to macroscopic flow outputs, bypassing traditional aggregate time-series sequences.

## Archivist Review

I approved 'State-to-Flow Modeling' as a core paradigm shift in time-series forecasting, preferring it over the specific 'AeroSense' implementation. The open question regarding scalability was refined to focus on the technical challenge of set-based representations in high-density, heterogeneous environments, ensuring it addresses a substantial bottleneck in the field.

### Approved Concepts
- State-to-Flow Modeling: This represents a significant methodological shift from aggregate time-series forecasting to set-based dynamical modeling in cyber-physical systems, which is highly reusable.

### Approved Open Questions
- Scalability of Set-based Air Traffic Forecasting: As a paradigm shift, validating the robust scaling of these set-based architectures is essential to determine if they can replace legacy time-series methods in operational settings.

### Rejected Candidates
- [concept] AeroSense (`aerosense`) - subcomponent_of_broader_mechanism: AeroSense is the paper-specific implementation of the broader 'State-to-Flow Modeling' paradigm; the latter is a more appropriate and reusable entry for the vault.
- [open_question] Scalability of Set-based Air Traffic Modeling (`scalability-of-set-based-air-traffic-modeling`) - duplicate_existing: The proposed question was rewritten for clarity and to better align with standard naming conventions while preserving the core technical research problem.

## Links

- [Abstract](https://arxiv.org/abs/2604.11198)
- [PDF](https://arxiv.org/pdf/2604.11198)

