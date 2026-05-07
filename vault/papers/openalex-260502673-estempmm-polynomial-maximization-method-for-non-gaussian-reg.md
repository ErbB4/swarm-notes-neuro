---
# CSL-compatible fields
title: "EstemPMM: Polynomial Maximization Method for Non-Gaussian Regression and Time Series in R"
author:
  - literal: "Serhii Zabolotnii"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02673"

# Custom fields
paper_id: "2605.02673"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "polynomial-maximization-method"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T06:03:57Z"
created_at: "2026-05-07T06:03:57Z"
---

# EstemPMM: Polynomial Maximization Method for Non-Gaussian Regression and Time Series in R

**Authors**: Serhii Zabolotnii
**Date**: 2026-05-04
**Paper ID**: [openalex:2605.02673](https://arxiv.org/abs/2605.02673)

## Summary

The paper presents the 'EstemPMM' R package, which implements the Polynomial Maximization Method (PMM) to improve parameter estimation in regression and time-series models with non-Gaussian, asymmetric, or leptokurtic errors. By incorporating higher-order cumulants, the PMM-based estimators achieve higher precision and asymptotic efficiency compared to standard OLS. The package includes an automated dispatch function and comprehensive diagnostic tools, with evaluation via Monte Carlo experiments and real-world financial time-series data.

## Key Contributions

- Introduces the R package 'EstemPMM' for parameter estimation using the Polynomial Maximization Method (PMM) under non-Gaussian error distributions.
- Provides a data-driven dispatch mechanism (pmm_dispatch) that automates the selection between OLS and higher-order PMM variants based on skewness and excess kurtosis.
- Demonstrates through Monte Carlo experiments and WTI crude-oil case studies that PMM estimators offer superior precision and asymptotic efficiency compared to OLS for heavy-tailed data.

## Key Concepts

- [[polynomial-maximization-method]]: A parameter estimation framework for regression and time-series models that utilizes higher-order cumulants to achieve efficiency gains over OLS in the presence of asymmetric or leptokurtic errors.

## Archivist Review

I have approved the Polynomial Maximization Method as a foundational concept for non-Gaussian parameter estimation. The specific dispatch implementation and the demo dataset were rejected as they represent local tooling or generic financial data rather than distinct, reusable research methodologies or critical benchmarks.

### Approved Concepts
- Polynomial Maximization Method (PMM): PMM provides a robust parameter estimation framework for non-Gaussian scenarios by leveraging higher-order moments, offering a distinct alternative to standard OLS.

### Rejected Candidates
- [concept] PMM Dispatch Mechanism (`pmm-dispatch-mechanism`) - subcomponent_of_broader_mechanism: The dispatch function is a local implementation detail of the R package, not a broad methodology.
- [dataset] WTI Crude-Oil dataset (`wti-crude-oil-dataset`) - not_novel: This is a standard commodity price series used for demonstration, not a novel or specialized benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2605.02673)
- [PDF](https://arxiv.org/pdf/2605.02673)

