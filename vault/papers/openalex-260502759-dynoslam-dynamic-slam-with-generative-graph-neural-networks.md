---
# CSL-compatible fields
title: "DynoSLAM: Dynamic SLAM with Generative Graph Neural Networks for Real-World Social Navigation"
author:
  - literal: "Danil Tokhchukov"
  - literal: "Veronika Morozova"
  - literal: "Gonzalo Ferrer"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02759"

# Custom fields
paper_id: "2605.02759"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "robotics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dynamic-graphslam"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:05:14Z"
created_at: "2026-05-07T06:05:14Z"
---

# DynoSLAM: Dynamic SLAM with Generative Graph Neural Networks for Real-World Social Navigation

**Authors**: Danil Tokhchukov, Veronika Morozova, Gonzalo Ferrer
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02759](https://arxiv.org/abs/2605.02759)

## Summary

DynoSLAM is a dynamic SLAM architecture designed for navigation in crowded environments by relaxing the static-world assumption. It integrates socially-aware GNNs directly into factor graph optimization, treating pedestrian motion as a stochastic process rather than a deterministic heuristic. By utilizing Monte Carlo rollouts to derive mean and covariance for future states, the model provides a probabilistic safety envelope that significantly improves tracking robustness compared to traditional approaches.

## Key Contributions

- Introduces DynoSLAM, a dynamic SLAM framework that integrates socially-aware GNNs into factor graph optimization.
- Formulates pedestrian motion forecasting as a stochastic world model to capture multimodal uncertainty.
- Implements a dynamic Mahalanobis distance factor to embed epistemic uncertainty into the optimization, mitigating the 'argmax' failure mode in tracking.

## Open Questions & Future Work

- [[generative-flow-matching-for-stochastic-motion-prediction]]

## Key Concepts

- [[dynamic-graphslam]]: A SLAM framework that incorporates socially-aware GNNs for motion forecasting directly into factor graph optimization.

## Archivist Review

I approved the 'Dynamic GraphSLAM' concept because it introduces a novel, reusable mechanism for integrating neural motion priors into factor graph-based SLAM, which is central to the paper's contribution. The open question regarding 'Generative Flow Matching for Motion Prediction' was also approved as it identifies a clear, theoretically grounded path for improving uncertainty estimation beyond current sampling-based surrogate methods in dynamic robotics.

### Approved Concepts
- Dynamic GraphSLAM: It provides a way to incorporate stochastic, interaction-aware neural priors directly into SLAM optimization frameworks, moving beyond rigid heuristic motion models in dynamic environments.

### Approved Open Questions
- Generative Flow Matching for Motion Prediction: This shift from surrogate noise to learned generative dynamics is essential for improving the accuracy and theoretical grounding of uncertainty estimation in complex human-robot interaction scenarios.

## Links

- [Abstract](https://arxiv.org/abs/2605.02759)
- [PDF](https://arxiv.org/pdf/2605.02759)

