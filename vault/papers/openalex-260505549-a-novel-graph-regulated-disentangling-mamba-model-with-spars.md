---
# CSL-compatible fields
title: "A Novel Graph-Regulated Disentangling Mamba Model with Sparse Tokens for Enhanced Tree Species Classification from MODIS Time Series"
author:
  - literal: "Motasem Alkayid"
  - literal: "Zhengsen Xu"
  - literal: "Saeid Taleghanidoozdoozan"
  - literal: "Yimin Zhu"
  - literal: "Megan Greenwood"
  - literal: "Quinn Ledingham"
  - literal: "Zack Dewis"
  - literal: "Mabel Heffring"
  - literal: "Naser El-Sheimy"
  - literal: "Lincoln Linlin Xu"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05549"

# Custom fields
paper_id: "2605.05549"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "time-series-forecasting"
  - "graph-neural-networks"
  - "remote-sensing"
  - "state-space-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "gds-mamba-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:10Z"
created_at: "2026-05-10T06:04:10Z"
---

# A Novel Graph-Regulated Disentangling Mamba Model with Sparse Tokens for Enhanced Tree Species Classification from MODIS Time Series

**Authors**: Motasem Alkayid, Zhengsen Xu, Saeid Taleghanidoozdoozan, Yimin Zhu, Megan Greenwood, Quinn Ledingham, Zack Dewis, Mabel Heffring, Naser El-Sheimy, Lincoln Linlin Xu
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05549](https://arxiv.org/abs/2605.05549)

## Summary

This paper introduces GDS-Mamba, a novel architecture for tree species classification that improves upon standard Mamba state space models by incorporating graph-based topological modeling, feature disentanglement, and adaptive sparse token selection. By explicitly separating spatial, spectral, and temporal phenology components, the model better handles the high-dimensional coupling inherent in MODIS satellite time series. Experimental results on MOD13Q1 data across Canadian regions demonstrate superior classification accuracy and efficiency compared to twelve state-of-the-art benchmarks.

## Key Contributions

- Introduced the Graph-regulated Disentangled Sparse Mamba (GDS-Mamba) architecture to address high-dimensional spatial-spectral-temporal coupling in MODIS data.
- Developed a mini-batch graph-regulated approach to explicitly capture topological correlations across large-scale remote sensing imagery.
- Designed an adaptive sparse token mechanism to mitigate correlation decay in Mamba, achieving 93.94% overall accuracy on MOD13Q1 datasets.

## Open Questions & Future Work

- [[optimizing-sparse-mamba-tokens]]

## Key Concepts

- [[gds-mamba-model]]: A hybrid Mamba-based architecture designed to disentangle spatial-spectral-temporal features and model topological context via graph regulation.

## Archivist Review

Approved the GDS-Mamba architecture and the open question regarding sparse token optimization in Mamba models. Rejected the dataset candidate as it is a routine remote sensing product, not a specialized benchmark dataset. Applied a strict interpretation of architectural novelty and foundational open problems in state space modeling.

### Approved Concepts
- Graph-regulated Disentangled Sparse Mamba (GDS-Mamba): Combines graph-based regularization with state space models to address high-dimensional spatial-spectral-temporal coupling in time series data.

### Approved Open Questions
- Optimizing Sparse Mamba Tokens: Sparse tokens are essential for scaling state space models to long sequences while maintaining performance, and resolving the bottleneck of correlation decay is a primary challenge for this architecture's adoption.

### Rejected Candidates
- [dataset] MOD13Q1 (`mod13q1`) - not_novel: Routine satellite imagery product that does not qualify as a curated or novel dataset benchmark worthy of a permanent note.

## Links

- [Abstract](https://arxiv.org/abs/2605.05549)
- [PDF](https://arxiv.org/pdf/2605.05549)

