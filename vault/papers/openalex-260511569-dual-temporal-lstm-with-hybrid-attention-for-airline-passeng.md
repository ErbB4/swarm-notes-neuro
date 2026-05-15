---
# CSL-compatible fields
title: "Dual-Temporal LSTM with Hybrid Attention for Airline Passenger Load Factor Forecasting: Integrating Intra-Flight and Inter-Flight Booking Dynamics"
author:
  - literal: "ASM Nazrul Islam"
  - literal: "Md. Hasanul Kabir"
  - literal: "Md. Liakot Ali"
  - literal: "Joydeb Kumar Sana"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11569"

# Custom fields
paper_id: "2605.11569"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dual-temporal-booking-representation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:15:16Z"
created_at: "2026-05-15T06:15:16Z"
---

# Dual-Temporal LSTM with Hybrid Attention for Airline Passenger Load Factor Forecasting: Integrating Intra-Flight and Inter-Flight Booking Dynamics

**Authors**: ASM Nazrul Islam, Md. Hasanul Kabir, Md. Liakot Ali, Joydeb Kumar Sana
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.11569](https://arxiv.org/abs/2605.11569)

## Summary

This paper addresses the limitations of unidimensional booking demand forecasting in the airline industry by proposing a dual-stream LSTM framework. The model simultaneously captures intra-flight booking accumulation and inter-flight patterns using hybrid attention mechanisms, which improves upon traditional single-stream approaches. By predicting load factors rather than absolute passenger counts, the model remains resilient to aircraft capacity changes. Experimental results on proprietary data from Biman Bangladesh Airlines demonstrate significant improvements in forecast accuracy and operational robustness compared to existing baselines.

## Key Contributions

- Introduces a dual-stream LSTM architecture that jointly processes intra-flight booking accumulation and inter-flight historical booking patterns.
- Develops hybrid attention mechanisms (combining self-attention and cross-attention) to effectively fuse horizontal and vertical booking temporal dimensions.
- Achieves superior forecasting performance on real-world airline reservation data with a Mean Absolute Error of 2.8167 and R² of 0.9495.
- Demonstrates robust generalization across four distinct flight category pairings (e.g., domestic/international, direct/transit).

## Open Questions & Future Work

- [[cabin-level-plf-forecasting-bottleneck]]

## Key Concepts

- [[dual-temporal-booking-representation]]: A forecasting representation that concurrently models intra-event accumulation dynamics and inter-event historical patterns to improve prediction robustness.

## Archivist Review

I approved the dual-temporal representation as a reusable architectural pattern for modeling business-process-based time series. I also approved a refined version of the cabin-level forecasting open question, as it highlights a substantial gap in moving from aggregate demand models to actionable yield management systems. Other items were rejected as they were either too specific to the airline application or represented routine model extensions.

### Approved Concepts
- Dual-Temporal Booking Representation: This architecture provides a structured way to handle multidimensional time-series data where temporal axes represent different business dynamics (accumulation vs. recurring historical patterns), which is highly reusable in supply chain and demand forecasting.

### Approved Open Questions
- Cabin-Level PLF Forecasting Bottleneck: Moving from aggregate to granular forecasting is a fundamental bottleneck for deploying predictive models in production-grade revenue management systems.

### Rejected Candidates
- [open_question] Cabin-Level PLF Forecasting Extension (`cabin-level-plf-forecasting`) - duplicate_existing: Renamed to align with standard naming conventions for research bottlenecks.

## Links

- [Abstract](https://arxiv.org/abs/2605.11569)
- [PDF](https://arxiv.org/pdf/2605.11569)

