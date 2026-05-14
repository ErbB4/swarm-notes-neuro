---
# CSL-compatible fields
title: "Set Prediction for Next-Day Active Fire Forecasting"
author:
  - literal: "Yuchen Bai"
  - literal: "Georgios Athanasiou"
  - literal: "Xin Yu"
  - literal: "Diogenis Antonopoulos"
  - literal: "Ioannis Papoutsis"
  - literal: "Stijn Hantson"
  - literal: "Nuno Carvalhais"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10298"

# Custom fields
paper_id: "2605.10298"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "remote-sensing"
  - "spatio-temporal-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "wildfire-ignition-set-predictor-wisp"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:09:48Z"
created_at: "2026-05-14T06:09:48Z"
---

# Set Prediction for Next-Day Active Fire Forecasting

**Authors**: Yuchen Bai, Georgios Athanasiou, Xin Yu, Diogenis Antonopoulos, Ioannis Papoutsis, Stijn Hantson, Nuno Carvalhais
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10298](https://arxiv.org/abs/2605.10298)

## Summary

The paper introduces the Wildfire Ignition Set Predictor (WISP), a query-based framework that shifts wildfire forecasting from traditional grid-based probability mapping to point-set prediction of active fire cluster centers. By leveraging Hungarian matching and asymmetric classification-localization weighting, the model effectively identifies and localizes discrete fire events at a 375m resolution. The approach is validated against a new globally distributed, multi-source benchmark, demonstrating significant capability in both detection precision and fire radiative power coverage.

## Key Contributions

- Proposes Wildfire Ignition Set Predictor (WISP), a query-based model that reformulates wildfire forecasting as a point-set prediction problem on 375m grids.
- Introduces an asymmetric classification-localization weighting strategy to resolve conflicting roles of classification scores in matching and query activation.
- Achieves 38.2% average precision and localizes 54.1% of fire clusters within 5 km on a new globally distributed, multi-source fire benchmark.

## Open Questions & Future Work

- [[decoupling-score-roles-in-sparse-set-prediction]]

## Key Concepts

- [[wildfire-ignition-set-predictor-wisp]]: A query-based model that treats next-day wildfire active fire forecasting as a point-set prediction task using Hungarian matching.

## Archivist Review

I have approved the WISP architecture as a novel approach to geospatial forecasting and the open question regarding score-role conflicts in set prediction. The other components were rejected as they were either specific implementations or already addressed by the approved broader concepts.

### Approved Concepts
- Wildfire Ignition Set Predictor (WISP): Introduces a novel query-based set prediction paradigm for localized wildfire event forecasting, shifting from grid-based probability maps to point-set estimation.

### Approved Open Questions
- Decoupling Score Roles in Set Prediction: Decoupling these roles is essential for achieving reliable uncertainty estimation and avoiding issues such as duplicate detections or poor ranking of predicted fire queries, which are critical for the operational use of wildfire forecasts in disaster management.

## Links

- [Abstract](https://arxiv.org/abs/2605.10298)
- [PDF](https://arxiv.org/pdf/2605.10298)

