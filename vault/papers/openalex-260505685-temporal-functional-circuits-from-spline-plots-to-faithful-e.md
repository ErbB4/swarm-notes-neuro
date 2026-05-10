---
# CSL-compatible fields
title: "Temporal Functional Circuits: From Spline Plots to Faithful Explanations in KAN Forecasting"
author:
  - literal: "Naveen Mysore"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05685"

# Custom fields
paper_id: "2605.05685"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "interpretability"
  - "kolmogorov-arnold-network"
architectures:
  []
datasets:
  []
concept_slugs:
  - "temporal-functional-circuits"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:03:56Z"
created_at: "2026-05-10T06:03:56Z"
---

# Temporal Functional Circuits: From Spline Plots to Faithful Explanations in KAN Forecasting

**Authors**: Naveen Mysore
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05685](https://arxiv.org/abs/2605.05685)

## Summary

This paper presents Temporal Functional Circuits, a novel framework for enhancing the interpretability of Kolmogorov-Arnold Networks (KANs) in time-series forecasting. By utilizing a gated residual structure, the model separates forecasts into a linear base and a sparse, spline-based correction, allowing for direct mapping of edge functions to input lags. The framework employs attribution techniques and edge-level interventions, such as spline removal, to validate the faithfulness of learned explanations. Experimental results demonstrate competitive performance against standard baselines while providing superior mechanistic insights.

## Key Contributions

- Introduces Temporal Functional Circuits to provide faithful, temporally grounded explanations for KAN-based time-series forecasts.
- Develops a gated residual KAN architecture that decomposes forecasts into a linear base and a sparsely activated spline-based correction.
- Demonstrates 59% lower MSE compared to linear models on regime-switching signals and provides competitive performance with state-of-the-art baselines across eight benchmarks.

## Open Questions & Future Work

- [[automated-gate-regularization-tuning]]
- [[semantic-grounding-of-kan-functions]]

## Key Concepts

- [[temporal-functional-circuits]]: A framework for interpreting Kolmogorov-Arnold Network edge functions in time-series forecasting through temporal attribution and edge-level intervention analysis.

## Archivist Review

The paper proposes a useful framework for KAN interpretability in time series, which is approved as a new concept. The open questions regarding automated sparsity tuning and semantic alignment of learned functions are substantial enough for tracking in the vault. No datasets were approved as the paper utilizes common benchmarks rather than a new critical source.

### Approved Concepts
- Temporal Functional Circuits: It enables mechanistic interpretability in KAN-based time-series forecasting by mapping edge functions to specific input lags and verifying their predictive contribution.

### Approved Open Questions
- Automated gate regularization tuning: The gate's sparsity penalty is critical for balancing model accuracy and interpretability; without automated tuning, the utility of the gated diagnostic is limited by the labor-intensive requirement for manual hyperparameter selection per dataset.
- Semantic grounding of KAN functions: Bridging the gap between mathematical transparency and human semantic understanding is essential for the practical adoption of inherently interpretable models in fields where stakeholders must trust and act upon machine-generated forecasts.

## Links

- [Abstract](https://arxiv.org/abs/2605.05685)
- [PDF](https://arxiv.org/pdf/2605.05685)

