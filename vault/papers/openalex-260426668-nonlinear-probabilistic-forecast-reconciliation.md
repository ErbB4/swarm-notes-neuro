---
# CSL-compatible fields
title: "Nonlinear Probabilistic Forecast Reconciliation"
author:
  - literal: "Avizit Biswas"
  - literal: "Lorenzo Zambon"
  - literal: "Lorenzo Nespoli"
  - literal: "Giorgio Corani"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26668"

# Custom fields
paper_id: "2604.26668"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "probabilistic-forecast-reconciliation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:49:29Z"
created_at: "2026-05-02T05:49:29Z"
---

# Nonlinear Probabilistic Forecast Reconciliation

**Authors**: Avizit Biswas, Lorenzo Zambon, Lorenzo Nespoli, Giorgio Corani
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26668](https://arxiv.org/abs/2604.26668)

## Summary

This paper introduces a novel framework for probabilistic forecast reconciliation subject to nonlinear constraints, addressing a significant limitation in standard linear reconciliation methods. The authors extend both projection-based and conditioning-based approaches to the nonlinear regime, with the latter utilizing an Unscented Kalman Filter (UKF) inspired algorithm. Empirical results indicate that these methods consistently improve forecast accuracy, with the UKF-based approach demonstrating superior performance and efficiency.

## Key Contributions

- Introduces the first framework for probabilistic forecast reconciliation under nonlinear constraints, generalizing projection and conditioning techniques.
- Proposes a conditioning-based reconciliation method utilizing an Unscented Kalman Filter (UKF) architecture to achieve state-of-the-art accuracy and computational efficiency.
- Demonstrates through empirical evaluation on synthetic and real-world datasets that nonlinear reconciliation significantly improves forecast coherence and accuracy over independent forecasts.

## Open Questions & Future Work

- [[non-gaussian-nonlinear-reconciliation]]
- [[geodesic-evaluation-metrics]]

## Key Concepts

- [[probabilistic-forecast-reconciliation]]: A methodology for adjusting independent probabilistic forecasts to ensure they satisfy complex nonlinear coherence constraints.

## Archivist Review

The paper introduces a significant extension to forecast reconciliation by moving from linear to nonlinear constraints. I approved the core concept of nonlinear probabilistic reconciliation and two high-impact open questions regarding the Gaussian limitation and manifold-aware evaluation. These items are fundamental, reusable, and address specific theoretical bottlenecks in the field.

### Approved Concepts
- Probabilistic Forecast Reconciliation: It extends the field of forecast reconciliation from strictly linear to nonlinear constraints, which is a common requirement in physical and economic systems.

### Approved Open Questions
- Non-Gaussian Nonlinear Forecast Reconciliation: Many real-world forecasting applications, such as demand or count-based monitoring, involve non-Gaussian variables that render current nonlinear reconciliation techniques inapplicable.
- Geodesic-based Forecast Evaluation Metrics: Misalignment between the evaluation metric and the underlying geometry of the forecast space can lead to inaccurate performance assessment and suboptimal model selection.

## Links

- [Abstract](https://arxiv.org/abs/2604.26668)
- [PDF](https://arxiv.org/pdf/2604.26668)

