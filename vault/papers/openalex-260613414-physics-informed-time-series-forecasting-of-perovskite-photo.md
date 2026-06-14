---
# CSL-compatible fields
title: "Physics-informed time-series forecasting of perovskite photoluminescence stability"
author:
  - literal: "Alexander Wieczorek"
  - literal: "Manuel Kober‐Czerny"
  - literal: "Fábio Lopes"
  - literal: "Austin George Kuba"
  - literal: "L. Müller"
  - literal: "Christian M. Wolff"
  - literal: "Jason Hattrick-Simpers"
  - literal: "Sebastian Siol"
issued:
  date-parts:
    - [2026, 6, 11]
url: "https://arxiv.org/abs/2606.13414"

# Custom fields
paper_id: "2606.13414"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-informed-time-series-forecasting"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-14T06:33:08Z"
created_at: "2026-06-14T06:33:08Z"
---

# Physics-informed time-series forecasting of perovskite photoluminescence stability

**Authors**: Alexander Wieczorek, Manuel Kober‐Czerny, Fábio Lopes, Austin George Kuba, L. Müller, Christian M. Wolff, Jason Hattrick-Simpers, Sebastian Siol
**Date**: 2026-06-11
**Paper ID**: [openalex:2606.13414](https://arxiv.org/abs/2606.13414)

## Summary

This paper presents a physics-informed forecasting framework to predict the long-term photoluminescence (PL) stability of metal halide perovskites under accelerated aging conditions. The method featurizes PL spectra using domain-specific physical models and employs a hybrid CNN-LSTM architecture for time-series forecasting. Evaluation on a dataset of 167 perovskites shows that the model achieves superior performance over baselines and provides interpretable stability descriptors, facilitating faster material discovery and testing.

## Key Contributions

- Introduces a physics-informed time-series forecasting framework for predicting long-term photoluminescence stability in metal halide perovskites.
- Curates a dataset of 167 perovskite materials comprising over 86k photoluminescence spectra under heat and light stress.
- Demonstrates that combining physics-based featurization with a hybrid CNN-LSTM architecture outperforms baseline benchmarks while maintaining interpretability.

## Key Concepts

- [[physics-informed-time-series-forecasting]]: A forecasting framework that integrates physics-based featurization with neural architectures to predict temporal dynamics in material science.

## Archivist Review

The core contribution of physics-informed feature engineering for time-series forecasting is a valuable, reusable methodology. The hybrid CNN-LSTM architecture was rejected as it represents a generic implementation detail rather than a distinct, novel framework concept. No datasets or open questions were sufficiently distinct or critical to warrant permanent vault inclusion.

### Approved Concepts
- Physics-informed time-series forecasting: The core methodological contribution combines domain-specific physics knowledge with forecasting models to improve predictive performance and interpretability in material science applications.

### Rejected Candidates
- [concept] Hybrid CNN-LSTM architecture (`hybrid-cnn-lstm-architecture`) - not_novel: This is a routine neural network design rather than a novel or highly specific forecasting methodology.

## Links

- [Abstract](https://arxiv.org/abs/2606.13414)
- [PDF](https://arxiv.org/pdf/2606.13414)

