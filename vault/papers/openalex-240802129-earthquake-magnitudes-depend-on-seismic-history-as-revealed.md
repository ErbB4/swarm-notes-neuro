---
# CSL-compatible fields
title: "Earthquake magnitudes depend on seismic history, as revealed by a neural network analysis"
author:
  - literal: "Neri Berman"
  - literal: "Oleg Zlydenko"
  - literal: "Oren Gilon"
  - literal: "Yossi Matias"
  - literal: "Yohai Bar‐Sinai"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2408.02129"

# Custom fields
paper_id: "2408.02129"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "probabilistic-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "magnet-magnitude-neural-estimation-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:49Z"
created_at: "2026-05-10T06:04:49Z"
---

# Earthquake magnitudes depend on seismic history, as revealed by a neural network analysis

**Authors**: Neri Berman, Oleg Zlydenko, Oren Gilon, Yossi Matias, Yohai Bar‐Sinai
**Date**: 2026-05-07
**Paper ID**: [openalex:2408.02129](https://arxiv.org/abs/2408.02129)

## Summary

This paper investigates the long-standing debate regarding the predictability of earthquake magnitudes by challenging the traditional assumption that they follow a time-independent Gutenberg-Richter distribution. The authors introduce MAGNET, a multi-encoder LSTM-based model that processes spatiotemporal patterns in historical hypocenter data to generate probabilistic magnitude forecasts. Empirical results across Southern California, Japan, and New Zealand catalogs reveal that seismic history contains significant predictive information, outperforming standard static models. These findings indicate that future earthquake magnitudes are more predictable than previously thought and provide a foundation for improved seismic hazard assessment.

## Key Contributions

- Introduces MAGNET, a multi-encoder neural model that uses spatiotemporal seismic history to forecast future earthquake magnitudes.
- Demonstrates that earthquake magnitude distributions are not independent of past seismic events, providing an average information gain of ~0.07 bits per event over the baseline Gutenberg-Richter model.
- Validates the predictive capability of seismic catalogs across diverse geographic regions including Southern California, Japan, and New Zealand.

## Open Questions & Future Work

- [[interpretability-of-magnitude-predictability-features]]

## Key Concepts

- [[magnet-magnitude-neural-estimation-model]]: A multi-encoder LSTM-based neural architecture designed to predict future earthquake magnitudes from spatiotemporal seismic history.

## Archivist Review

I approved the MAGNET architecture as a representative instance of sequential multi-encoder processing in geophysical time series and included the open question regarding the interpretability of magnitude predictability to address the physical/statistical gap between empirical performance and seismic theory. I rejected the regional seismic datasets as they are standard, geographically-bound collections that do not meet the criteria for specialized, high-utility research dataset notes.

### Approved Concepts
- MAGNET (MAGnitude Neural EsTimation model): The model serves as the primary tool to demonstrate that earthquake magnitudes are not independent of seismic history, challenging the standard Gutenberg-Richter assumptions.

### Approved Open Questions
- Interpretability of magnitude predictability features: Understanding the causal features behind magnitude predictability is essential for bridging the gap between empirical neural network performance and the physical theory of earthquake rupture.

### Rejected Candidates
- [dataset] Southern California catalog (`southern-california-catalog`) - not_novel: Regional seismic catalogs are routine domain-specific data collections that do not merit permanent individual vault entries.
- [dataset] Japan seismic catalog (`japan-seismic-catalog`) - not_novel: Regional seismic catalogs are routine domain-specific data collections that do not merit permanent individual vault entries.
- [dataset] New Zealand seismic catalog (`new-zealand-seismic-catalog`) - not_novel: Regional seismic catalogs are routine domain-specific data collections that do not merit permanent individual vault entries.

## Links

- [Abstract](https://arxiv.org/abs/2408.02129)
- [PDF](https://arxiv.org/pdf/2408.02129)

