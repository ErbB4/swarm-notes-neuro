---
# CSL-compatible fields
title: "Differentiable latent structure discovery for interpretable forecasting in clinical time series"
author:
  - literal: "Ivan Lerner"
  - literal: "Jean Feydy"
  - literal: "Alexandre Kalimouttou"
  - literal: "Anita Burgun"
  - literal: "Francis Bach"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27967"

# Custom fields
paper_id: "2604.27967"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "interpretability"
  - "uncertainty-quantification"
  - "electronic-health-records"
architectures:
  []
datasets:
  []
concept_slugs:
  - "structgp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:02:36Z"
created_at: "2026-05-03T06:02:36Z"
---

# Differentiable latent structure discovery for interpretable forecasting in clinical time series

**Authors**: Ivan Lerner, Jean Feydy, Alexandre Kalimouttou, Anita Burgun, Francis Bach
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.27967](https://arxiv.org/abs/2604.27967)

## Summary

The paper introduces StructGP and its extension LP-StructGP for interpretable forecasting in irregular clinical time series. StructGP utilizes continuous-time multi-task Gaussian processes with differentiable structure learning to identify sparse DAGs of variable dependencies, while LP-StructGP incorporates latent pathways to capture cross-patient progression. Empirical results on MIMIC-IV and the PhysioNet Challenge show that these models provide superior calibration and accuracy compared to unstructured kernels and baseline methods.

## Key Contributions

- Introduced StructGP, a continuous-time multi-task Gaussian process that performs differentiable structure learning to recover sparse DAGs.
- Developed LP-StructGP, which uses subject-specific coupling filters and gating to capture shared cross-patient progression trajectories.
- Demonstrated superior forecasting accuracy and uncertainty calibration compared to unstructured kernels and independent-task baselines on MIMIC-IV septic shock data.

## Open Questions & Future Work

- [[non-gaussian-likelihoods-in-structured-process-convolutions]]

## Key Concepts

- [[structgp]]: A continuous-time multi-task Gaussian process that uncovers sparse, ordered DAGs of inter-variable dependencies using process convolutions.

## Archivist Review

The review prioritized the core contribution of differentiable structure learning within continuous-time Gaussian processes. StructGP was approved as a significant architectural paradigm. LP-StructGP was rejected as a subordinate model extension. One open question regarding the fundamental limitation of Gaussian assumptions in process convolutions was approved, while the scalability concern was rejected as a standard optimization challenge.

### Approved Concepts
- StructGP: The model introduces a novel way to combine differentiable structure learning (DAG recovery) with continuous-time multi-task Gaussian processes.

### Approved Open Questions
- Non-Gaussian Likelihoods for GPs: This is a fundamental bottleneck for deploying continuous-time Gaussian process models in real-world clinical or physical systems that are not inherently Gaussian.

### Rejected Candidates
- [concept] LP-StructGP (`lp-structgp`) - subcomponent_of_broader_mechanism: This is a specific extension of the primary StructGP model and does not warrant a separate entry.
- [open_question] Scalability of latent pathway GPs (`scalability-of-latent-pathway-gp-models`) - low_impact: This is essentially a parameter scaling and efficiency problem which is common in model development, rather than a fundamental research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.27967)
- [PDF](https://arxiv.org/pdf/2604.27967)

