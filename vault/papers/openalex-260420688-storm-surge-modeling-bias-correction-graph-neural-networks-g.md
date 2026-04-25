---
# CSL-compatible fields
title: "Storm Surge Modeling, Bias Correction, Graph Neural Networks, Graph Convolution Networks"
author:
  - literal: "Noujoud Nader"
  - literal: "Stefanos Giaremis"
  - literal: "Clint Dawson"
  - literal: "Carola Kaiser"
  - literal: "Karame Mohammadiporshokooh"
  - literal: "Hartmut Kaiser"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20688"

# Custom fields
paper_id: "2604.20688"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "graph-neural-networks"
  - "spatio-temporal"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stormnet"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:38:17Z"
created_at: "2026-04-25T05:38:17Z"
---

# Storm Surge Modeling, Bias Correction, Graph Neural Networks, Graph Convolution Networks

**Authors**: Noujoud Nader, Stefanos Giaremis, Clint Dawson, Carola Kaiser, Karame Mohammadiporshokooh, Hartmut Kaiser
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20688](https://arxiv.org/abs/2604.20688)

## Summary

This paper presents StormNet, a spatio-temporal graph neural network designed to correct biases in high-fidelity numerical storm surge models like ADCIRC. By leveraging graph convolutions and attention mechanisms alongside LSTM layers, the framework captures the complex spatial dependencies of coastal gauge stations and their temporal evolution. Evaluated on Hurricane Idalia (2023), the model significantly reduces RMSE for 48- and 72-hour forecasting horizons and offers computational efficiency suitable for operational real-time deployment.

## Key Contributions

- Introduces StormNet, a novel spatio-temporal GNN combining GCN, GAT, and LSTM for storm surge forecast bias correction.
- Reduces RMSE in water-level predictions by >70% for 48-hour forecasts and >50% for 72-hour forecasts compared to raw numerical models.
- Demonstrates superior predictive performance over sequential LSTM baselines, particularly for longer temporal horizons.

## Open Questions & Future Work

- [[bias-correction-for-ungauged-coastal-locations]]

## Key Concepts

- [[stormnet]]: A spatio-temporal graph neural network architecture combining GCN, GAT, and LSTM components for bias correction of high-fidelity numerical weather model outputs.

## Archivist Review

I have approved the StormNet architecture as a reusable GNN-LSTM hybrid for bias correction in geophysical modeling. I also approved the open question regarding bias correction for ungauged locations, as it addresses a fundamental limitation in applying these models to real-world infrastructure gaps. I rejected no candidates because the initial submission was highly focused.

### Approved Concepts
- StormNet: Represents a specific hybrid architecture (GCN-GAT-LSTM) for the bias correction of complex physical models, which is a reusable strategy in geophysical forecasting.

### Approved Open Questions
- Bias correction for ungauged locations: Critical for expanding the real-world utility of GNN-based bias correction in coastal risk assessment, as most vulnerable locations lack dense sensor networks.

## Links

- [Abstract](https://arxiv.org/abs/2604.20688)
- [PDF](https://arxiv.org/pdf/2604.20688)

