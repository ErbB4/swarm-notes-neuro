---
# CSL-compatible fields
title: "Step-adaptive multimodal fusion network with multi-scale cloud feature learning for ultra-short-term solar irradiance forecasting"
author:
  - literal: "Jingxin Zhang"
  - literal: "Xiaoqin Wang"
issued:
  date-parts:
    - [2026, 6, 4]
url: "https://arxiv.org/abs/2606.06102"

# Custom fields
paper_id: "2606.06102"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "NREL dataset"
concept_slugs:
  - "step-adaptive-low-frequency-compensation"
dataset_slugs:
  - "nrel-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-06-07T06:32:27Z"
created_at: "2026-06-07T06:32:27Z"
---

# Step-adaptive multimodal fusion network with multi-scale cloud feature learning for ultra-short-term solar irradiance forecasting

**Authors**: Jingxin Zhang, Xiaoqin Wang
**Date**: 2026-06-04
**Paper ID**: [openalex:2606.06102](https://arxiv.org/abs/2606.06102)

## Summary

This paper addresses the challenges of ultra-short-term solar irradiance forecasting by proposing a multimodal fusion network that integrates ground-based cloud images with meteorological time-series data. The framework utilizes InceptionNeXt for multi-scale spatial feature extraction and a novel step-adaptive low-frequency compensation unit to adjust global information dynamically based on the forecast horizon. Combined with a TempAttnLSTM for capturing temporal dependencies, the method provides improved prediction accuracy compared to existing state-of-the-art models on NREL and practical datasets.

## Key Contributions

- Proposes a multi-source fusion model using InceptionNeXt for multi-scale spatial cloud feature extraction.
- Introduces a step-adaptive low-frequency compensation unit to dynamically modulate global information across different forecast horizons.
- Demonstrates superior performance over state-of-the-art methods for ultra-short-term solar irradiance forecasting on NREL and real-world photovoltaic station data.

## Key Concepts

- [[step-adaptive-low-frequency-compensation]]: A mechanism that dynamically modulates global frequency components conditioned on the specific forecast step in time-series prediction.

## Archivist Review

I approved the 'Step-adaptive Low-Frequency Compensation' concept as it represents a novel and reusable inductive bias for time-series forecasting that specifically addresses the horizon-dependent nature of spectral features. The NREL dataset was approved as a core evaluation benchmark. Other proposed elements were rejected as being either too specific to this implementation (e.g., InceptionNeXt/TempAttnLSTM integration) or insufficiently novel as standalone contributions.

### Approved Concepts
- Step-adaptive Low-Frequency Compensation: It addresses the failure of fixed frequency compensation strategies in ultra-short-term forecasting by allowing modulation tuned to the specific prediction horizon.

## Datasets

- [[nrel-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2606.06102)
- [PDF](https://arxiv.org/pdf/2606.06102)

