---
# CSL-compatible fields
title: "MambaSL: Exploring Single-Layer Mamba for Time Series Classification"
author:
  - literal: "Yoo-Min Jung"
  - literal: "Leekyung Kim"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.15174"

# Custom fields
paper_id: "2604.15174"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "uea-archive"
concept_slugs:
  []
dataset_slugs:
  - "uea-archive"
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:44:27Z"
created_at: "2026-04-19T05:44:27Z"
---

# MambaSL: Exploring Single-Layer Mamba for Time Series Classification

**Authors**: Yoo-Min Jung, Leekyung Kim
**Date**: 2026-04-16
**Paper ID**: [openalex:2604.15174](https://arxiv.org/abs/2604.15174)

## Summary

MambaSL explores the potential of single-layer selective state space models (SSMs) as a lightweight backbone for time series classification (TSC). The authors redesign selective SSM and projection layers guided by domain-specific hypotheses and provide a robust, unified evaluation protocol across all 30 University of East Anglia (UEA) datasets. Empirical results show that MambaSL achieves state-of-the-art performance, highlighting the effectiveness of highly efficient, shallow SSMs for sequential classification tasks.

## Key Contributions

- Introduces MambaSL, a minimally redesigned single-layer selective state space model framework for time series classification.
- Establishes a unified, reproducible evaluation protocol for time series classification across all 30 UEA archive datasets.
- Demonstrates state-of-the-art classification performance using a lightweight, single-layer Mamba backbone compared to 20 strong existing baselines.

## Open Questions & Future Work

- [[optimal-ssm-time-variance-configuration]]

## Archivist Review

I have approved the UEA archive as a critical dataset for time series classification benchmarking and the open question regarding SSM time-variance configurations. The MambaSL architecture itself was rejected as a local implementation detail, as it is a specific instantiation rather than a generalized methodological advancement. The review process prioritized foundational research questions over model-specific frameworks.

### Approved Open Questions
- Optimal SSM Time-Variance Configuration: Identifying the correct balance of time-invariance versus time-variance is critical for adapting Mamba-based models to time series data, where signal properties vary significantly. Misconfiguring these SSM components can impair classification accuracy.

### Rejected Candidates
- [concept] MambaSL (`mambasl`) - paper_local: This is a specific framework architecture and implementation rather than a general-purpose, reusable concept in the broader time series field.

## Datasets

- [[uea-archive]]

## Links

- [Abstract](https://arxiv.org/abs/2604.15174)
- [PDF](https://arxiv.org/pdf/2604.15174)

