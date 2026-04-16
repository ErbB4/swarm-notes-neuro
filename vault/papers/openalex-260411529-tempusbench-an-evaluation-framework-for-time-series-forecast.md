---
# CSL-compatible fields
title: "TempusBench: An Evaluation Framework for Time-Series Forecasting"
author:
  - literal: "Denizalp Goktas"
  - literal: "Gerardo Riaño‐Briceño"
  - literal: "Alif Abdullah"
  - literal: "Aryan Nair"
  - literal: "Chenkai Shen"
  - literal: "Beatriz de Lucio"
  - literal: "Alexandra Magnusson"
  - literal: "Farhan Mashrur"
  - literal: "Ahmed Abdulla"
  - literal: "Shawrna Sen"
  - literal: "Mahitha Thippireddy"
  - literal: "Gregory Schwartz"
  - literal: "Amy Greenwald"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11529"

# Custom fields
paper_id: "2604.11529"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "benchmarking"
  - "foundation-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tempusbench"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:09Z"
created_at: "2026-04-16T05:46:09Z"
---

# TempusBench: An Evaluation Framework for Time-Series Forecasting

**Authors**: Denizalp Goktas, Gerardo Riaño‐Briceño, Alif Abdullah, Aryan Nair, Chenkai Shen, Beatriz de Lucio, Alexandra Magnusson, Farhan Mashrur, Ahmed Abdulla, Shawrna Sen, Mahitha Thippireddy, Gregory Schwartz, Amy Greenwald
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11529](https://arxiv.org/abs/2604.11529)

## Summary

TempusBench is a comprehensive open-source evaluation framework designed to address critical shortcomings in current time-series foundation model (TSFM) benchmarking, such as data leakage and inconsistent evaluation methodologies. The framework provides a curated collection of new datasets, novel task benchmarks that account for statistical properties like non-stationarity and seasonality, and a standardized hyperparameter tuning pipeline for fair model comparisons. Additionally, it offers a TensorBoard-based interface to facilitate the interpretation of comparative performance across diverse models.

## Key Contributions

- Introduces TempusBench, an evaluation framework that addresses data leakage and lack of standardization in TSFM benchmarking.
- Curates new, non-leaked datasets to ensure robust evaluation of time-series foundation models.
- Implements a standardized hyperparameter tuning protocol for fair comparison between TSFMs and domain-specific baselines (e.g., XGBoost).

## Open Questions & Future Work

- [[dynamic-time-series-benchmarking]]

## Key Concepts

- [[tempusbench]]: An open-source, comprehensive evaluation framework for time-series foundation models designed to mitigate data leakage and provide consistent benchmarking.

## Archivist Review

I have approved TempusBench as a significant contribution to standardized time-series evaluation and accepted the open question regarding dynamic benchmarking as a critical, long-term research problem for foundation models. I rejected no candidates; the structured rejection list reflects the metadata requirement, but in this specific instance, the single concept and single open question were both high-quality and unique to the vault.

### Approved Concepts
- TempusBench: It provides a standardized, systemic approach to addressing common flaws in TSFM evaluation, specifically data leakage and hyperparameter inconsistency.

### Approved Open Questions
- Dynamic Forecasting Benchmarking: Data leakage significantly undermines the validity of benchmark performance metrics for time-series foundation models, necessitating a shift toward dynamic, non-stationary test beds.

### Rejected Candidates
- [concept] TempusBench (`tempusbench`) - other: The concept is the framework itself; I have approved it, but the instruction is to be extremely selective.

## Links

- [Abstract](https://arxiv.org/abs/2604.11529)
- [PDF](https://arxiv.org/pdf/2604.11529)

