---
# CSL-compatible fields
title: "Forecasting Ionospheric Irregularities on GNSS Lines of Sight Using Dynamic Graphs with Ephemeris Conditioning"
author:
  - literal: "Mert Can Turkmen"
  - literal: "Eng Leong Tan"
  - literal: "Yee Hui Lee"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18379"

# Custom fields
paper_id: "2604.18379"
paper_source: "openalex"
domain: "time-series"
tags:
  - "graph-neural-networks"
  - "time-series-forecasting"
  - "binary-classification"
  - "spatio-temporal-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "ephemeris-conditioning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:47:15Z"
created_at: "2026-04-23T05:47:15Z"
---

# Forecasting Ionospheric Irregularities on GNSS Lines of Sight Using Dynamic Graphs with Ephemeris Conditioning

**Authors**: Mert Can Turkmen, Eng Leong Tan, Yee Hui Lee
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18379](https://arxiv.org/abs/2604.18379)

## Summary

IonoDGNN addresses the limitations of grid-based ionospheric forecasting by modeling the ionosphere as a dynamic graph defined by time-varying satellite-based pierce points. By leveraging the predictability of satellite orbits, the authors introduce ephemeris conditioning, which incorporates future graph structure into the predictive process. This approach enables the model to accurately forecast ionospheric irregularities on lines of sight that only appear within the forecast window. Evaluation on multi-year GNSS data shows substantial improvements over persistence baselines, particularly as lead times increase.

## Key Contributions

- Introduces IonoDGNN, a dynamic graph neural network model for ionospheric irregularity forecasting that avoids the information loss inherent in gridded data.
- Proposes ephemeris conditioning to enable predictions on satellite lines of sight that become active only during the forecast horizon.
- Achieves a Brier Skill Score of 0.49 and a PR-AUC of 0.75, consistently outperforming persistence baselines for lead times up to 2 hours.

## Limitations

The current scope is restricted to a co-located receiver pair in a specific equatorial region; generalization to global, varying atmospheric conditions remains a potential challenge.

## Open Questions & Future Work

- [[scalability-of-dynamic-ionospheric-graphs]]

## Key Concepts

- [[ephemeris-conditioning]]: A technique for conditioning dynamic graph forecasts on the known, predictable future graph topology derived from trajectory data.

## Archivist Review

I approved 'Ephemeris Conditioning' as it is a distinct, reusable method for leveraging known future system states in dynamic graph forecasting. I rejected the local dataset because it lacks the maturity of a broadly adopted benchmark. I reformulated the open question to be more general and focused on the technical challenges of scalability for dynamic graph structures in non-Euclidean, heterogeneous sensor environments.

### Approved Concepts
- Ephemeris Conditioning: It provides a novel mechanism to integrate deterministic future connectivity into dynamic graph forecasting for mobile sensor networks.

### Approved Open Questions
- Scalability of Dynamic Ionospheric Graphs: This addresses the gap between localized proof-of-concept and operational deployment for critical infrastructure space weather monitoring.

### Rejected Candidates
- [dataset] multi-GNSS Singapore dataset (`multi-gnss-singapore-dataset`) - not_reusable: Small-scale, localized dataset that is not a standardized or broadly recognized community benchmark.

## Links

- [Abstract](https://arxiv.org/abs/2604.18379)
- [PDF](https://arxiv.org/pdf/2604.18379)

