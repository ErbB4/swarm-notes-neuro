---
# CSL-compatible fields
title: "Attention-based Multi-modal Deep Learning Model of Spatio-temporal Crop Yield Prediction with Satellite, Soil and Climate Data"
author:
  - literal: "Gopal Krishna Shyam"
  - literal: "Ila Chandrakar"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19217"

# Custom fields
paper_id: "2604.19217"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:34Z"
created_at: "2026-04-24T05:51:34Z"
---

# Attention-based Multi-modal Deep Learning Model of Spatio-temporal Crop Yield Prediction with Satellite, Soil and Climate Data

**Authors**: Gopal Krishna Shyam, Ila Chandrakar
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19217](https://arxiv.org/abs/2604.19217)

## Summary

The paper presents the Attention-Based Multi-Modal Deep Learning Framework (ABMMDLF) for improved spatio-temporal crop yield prediction by fusing satellite, meteorological, and soil data. The model employs a CNN architecture for spatial feature extraction coupled with a Temporal Attention Mechanism to dynamically weigh phenological periods. Experimental results demonstrate that this multi-modal approach achieves an R^2 of 0.89, significantly surpassing traditional static forecasting techniques.

## Key Contributions

- Introduced the Attention-Based Multi-Modal Deep Learning Framework (ABMMDLF) for crop yield prediction.
- Integrated heterogeneous data sources including multi-year satellite imagery, high-resolution meteorological time-series, and soil property data.
- Achieved an R^2 score of 0.89, outperforming conventional single-modality baseline models.

## Open Questions & Future Work

- [[federated-learning-agricultural-data-privacy]]

## Archivist Review

I rejected the proposed framework as it is a specific model architecture tailored to a single domain application. I also rejected the blockchain-related open question, as it pertains to infrastructure and data integrity rather than the core predictive methodology or statistical bottlenecks of spatio-temporal forecasting. I approved the federated learning open question because distributed learning and privacy constraints represent a major, non-trivial, and recurring challenge in large-scale spatio-temporal forecasting.

### Approved Open Questions
- Federated Learning for Agricultural Privacy: This is technically important as agricultural yield data is often proprietary or subject to strict privacy regulations, and traditional centralized training methods are becoming increasingly untenable for large-scale, cross-regional model deployment.

### Rejected Candidates
- [concept] Attention-Based Multi-Modal Deep Learning Framework (ABMMDLF) (`abmmdlf-framework`) - not_novel: This is a specific application-layer framework rather than a novel, reusable mechanism.
- [open_question] Blockchain for Agricultural Data Integrity (`blockchain-integrity-agricultural-supply-chain`) - low_impact: Blockchain integration is an application-level infrastructure concern rather than a core bottleneck in the predictive modeling of time-series data.

## Links

- [Abstract](https://arxiv.org/abs/2604.19217)
- [PDF](https://arxiv.org/pdf/2604.19217)

