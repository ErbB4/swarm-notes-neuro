---
# CSL-compatible fields
title: "Large Spectrum Models (LSMs): Decoder-Only Transformer-Powered Spectrum Activity Forecasting via Tokenized RF Data"
author:
  - literal: "Mohammad Mosiur Lunar"
  - literal: "Mehmet C. Vuran"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10825"

# Custom fields
paper_id: "2605.10825"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "wireless-communications"
  - "large-language-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "rf-tokenizer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:06Z"
created_at: "2026-05-14T06:10:06Z"
---

# Large Spectrum Models (LSMs): Decoder-Only Transformer-Powered Spectrum Activity Forecasting via Tokenized RF Data

**Authors**: Mohammad Mosiur Lunar, Mehmet C. Vuran
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10825](https://arxiv.org/abs/2605.10825)

## Summary

The authors propose Large Spectrum Models (LSMs), a framework that adapts decoder-only transformer architectures for spectrum activity forecasting. By introducing an RF tokenizer to discretize raw IQ measurements into token sequences, the model enables the utilization of large-scale LLM architectures for wireless signal prediction. The approach is validated on an extensive 22 TB outdoor wireless dataset, demonstrating that scaling these models yields superior accuracy in spectrum forecasting compared to traditional methods.

## Key Contributions

- Introduces a novel RF tokenizer that converts raw IQ measurements into a structured vocabulary suitable for LLM processing.
- Develops Large Spectrum Models (LSMs) by fine-tuning established LLM architectures (e.g., Mistral-7B) on 8.4B tokens of spectrum data.
- Demonstrates that LSMs achieve a 3.25 dB RMSE on sub-GHz spectrum forecasting, while maintaining high performance across different geographic deployment locations via fine-tuning.

## Open Questions & Future Work

- [[lsm-generalization-and-transfer-learning]]

## Key Concepts

- [[rf-tokenizer]]: A method for converting raw IQ measurements into token sequences by mapping spectral values, gain, frequency, and temporal data into a fixed vocabulary.

## Archivist Review

The proposed RF Tokenizer is a reusable methodology for adapting LLM architectures to raw signal data, representing a significant contribution to the field of spectrum forecasting. The open question on generalization addresses a major bottleneck in deploying these models across diverse, unseen wireless environments. I have maintained a strict stance on datasets, rejecting the 22TB proprietary dataset as it is not an established, broadly accessible community resource.

### Approved Concepts
- RF Tokenizer: Enables the application of LLM architectures to raw RF spectral data by discretizing continuous signal measurements into sequences.

### Approved Open Questions
- Generalization of Large Spectrum Models: Establishing the cross-site generalization capability of LSMs is essential to determine if these models can serve as foundational, ready-to-deploy intelligence for dynamic spectrum access without requiring extensive site-specific training.

## Links

- [Abstract](https://arxiv.org/abs/2605.10825)
- [PDF](https://arxiv.org/pdf/2605.10825)

