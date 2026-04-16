---
# CSL-compatible fields
title: "Physics-Informed State Space Models for Reliable Solar Irradiance Forecasting in Off-Grid Systems"
author:
  - literal: "Mohammed Ezzaldin Babiker Abdullah"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11807"

# Custom fields
paper_id: "2604.11807"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "thermodynamic-liquid-manifold-network"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:39Z"
created_at: "2026-04-16T05:46:39Z"
---

# Physics-Informed State Space Models for Reliable Solar Irradiance Forecasting in Off-Grid Systems

**Authors**: Mohammed Ezzaldin Babiker Abdullah
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11807](https://arxiv.org/abs/2604.11807)

## Summary

This paper introduces the Thermodynamic Liquid Manifold Network, a physics-informed deep learning architecture designed for robust solar irradiance forecasting in off-grid photovoltaic systems. By projecting meteorological data onto a Koopman-linearized Riemannian manifold and enforcing celestial geometry constraints, the model eliminates common issues like phase lags and nocturnal power artifacts. Validated over a five-year period in a semi-arid climate, the framework demonstrates high predictive accuracy and extreme efficiency, making it suitable for edge-deployed microgrid control.

## Key Contributions

- Introduces the Thermodynamic Liquid Manifold Network, achieving an RMSE of 18.31 Wh/m2 and a Pearson correlation of 0.988 for solar irradiance forecasting.
- Integrates a Spectral Calibration unit and a multiplicative Thermodynamic Alpha-Gate to ensure strict compliance with celestial geometry.
- Demonstrates complete elimination of nocturnal generation anomalies and sub-30-minute phase response during rapid cloud transients over a five-year testing horizon.
- Provides an ultra-lightweight, edge-deployable model with 63,458 parameters suitable for autonomous off-grid microgrid controllers.

## Key Concepts

- [[thermodynamic-liquid-manifold-network]]: A neural network architecture that projects meteorological data into a Koopman-linearized Riemannian manifold to enforce physical constraints on solar irradiance.

## Archivist Review

The review process prioritized the core methodological innovation—the Thermodynamic Liquid Manifold Network—as it provides a robust, reusable framework for embedding physical constraints into state-space models via Koopman linearization. Sub-components like the calibration unit and alpha-gate were rejected as they are domain-specific implementation details that do not yet warrant independent conceptual status. No open questions were approved, as the current evaluation presents the approach as a mature solution for the described task.

### Approved Concepts
- Thermodynamic Liquid Manifold Network: It is the core architectural contribution, combining Koopman operator theory with geometric constraints for time-series forecasting.

### Rejected Candidates
- [concept] Spectral Calibration unit (`spectral-calibration-unit`) - subcomponent_of_broader_mechanism: This is a sub-module of the main architecture and lacks independent conceptual standing outside of this specific implementation.
- [concept] Thermodynamic Alpha-Gate (`thermodynamic-alpha-gate`) - subcomponent_of_broader_mechanism: This is a specific gate mechanism internal to the proposed architecture and not a widely applicable primitive.

## Links

- [Abstract](https://arxiv.org/abs/2604.11807)
- [PDF](https://arxiv.org/pdf/2604.11807)

