---
# CSL-compatible fields
title: "Global Offshore Wind Infrastructure: Deployment and Operational Dynamics from Dense Sentinel-1 Time Series"
author:
  - literal: "Thorsten Hoeser"
  - literal: "Felix Bachofer"
  - literal: "Claudia Kuenzer"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20822"

# Custom fields
paper_id: "2604.20822"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "sentinel-1-offshore-wind-corpus"
concept_slugs:
  []
dataset_slugs:
  - "sentinel-1-offshore-wind-corpus"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T05:37:28Z"
created_at: "2026-04-25T05:37:28Z"
---

# Global Offshore Wind Infrastructure: Deployment and Operational Dynamics from Dense Sentinel-1 Time Series

**Authors**: Thorsten Hoeser, Felix Bachofer, Claudia Kuenzer
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20822](https://arxiv.org/abs/2604.20822)

## Summary

This paper addresses the gap in temporally dense, semantically annotated data for monitoring offshore wind infrastructure by providing a global, decade-long Sentinel-1 SAR time series corpus. The authors compile over 14 million analysis-ready 1D SAR backscatter profiles representing construction and operational phases. By releasing both the large-scale corpus and a curated expert-annotated benchmark, this work provides a standardized foundation for evaluating time series classification and change detection methods in the renewable energy sector.

## Key Contributions

- Introduces a global Sentinel-1 SAR time series corpus of 15,606 offshore wind infrastructure sites containing 14.8 million event-labeled backscatter profiles.
- Provides an expert-annotated benchmark dataset of 553 time series with 328,657 event labels for training and validating infrastructure monitoring models.
- Establishes a baseline rule-based classifier for semantic event labeling of SAR profiles, achieving a macro F1 score of 0.84.

## Open Questions & Future Work

- [[early-onset-offshore-infrastructure-detection]]

## Archivist Review

The paper introduces a significant domain-specific dataset for monitoring offshore infrastructure using SAR time series. I have approved the primary corpus as a dataset note and an open question regarding early-onset detection, as these provide lasting value beyond the specific benchmarking results. Other candidates were rejected as sub-components or for being too closely tied to the specific paper's internal evaluation tasks.

### Approved Open Questions
- Early-Onset Offshore Infrastructure Detection: Robust early-onset detection is essential for proactive monitoring of renewable energy deployment and requires moving beyond static site-based time series analysis.

### Rejected Candidates
- [dataset] Sentinel-1 expert-annotated benchmark dataset (`sentinel-1-benchmark-dataset`) - subcomponent_of_broader_mechanism: This is a sub-component of the broader Sentinel-1 offshore wind corpus, and I am prioritizing the latter as the primary dataset note.

## Datasets

- [[sentinel-1-offshore-wind-corpus]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20822)
- [PDF](https://arxiv.org/pdf/2604.20822)

