---
# CSL-compatible fields
title: "A Taxonomy of Event-Linked Perpetual Futures: Variant Designs Beyond the Single-Market Binary Case"
author:
  - literal: "Maksym Nechepurenko"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10428"

# Custom fields
paper_id: "2605.10428"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:11:00Z"
created_at: "2026-05-14T06:11:00Z"
---

# A Taxonomy of Event-Linked Perpetual Futures: Variant Designs Beyond the Single-Market Binary Case

**Authors**: Maksym Nechepurenko
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10428](https://arxiv.org/abs/2605.10428)

## Summary

This paper provides a theoretical taxonomy of event-linked perpetual futures, extending beyond basic binary prediction-market-based contracts to more complex instruments. It classifies seven canonical variants based on four design dimensions: underlying geometry, temporal structure, settlement structure, and venue composition. The work includes an inheritance map to determine how foundational risk-design components transfer to these variants, highlighting specific challenges such as denominator instability in conditional contracts and jump-aware margin aggregation in basket variants. The findings establish a framework for constructing and evaluating time-series data related to these derivative structures.

## Key Contributions

- Formalizes a taxonomy of seven canonical variants of event-linked perpetual futures beyond single-market binary contracts.
- Organizes design variants along four orthogonal axes: underlying geometry, temporal structure, settlement structure, and venue composition.
- Provides an inheritance framework identifying which risk-design components from base binary perpetuals are portable to more complex contract variants.

## Open Questions & Future Work

- [[conditional-probability-denominator-instability]]
- [[event-basket-rebalancing-uncertainty]]

## Archivist Review

The paper provides a theoretical taxonomy for event-linked financial instruments. While the taxonomy itself is a useful structural contribution, it functions more as a classification guide than as a standalone reusable concept in the context of the existing vault. The two open questions are approved as they address fundamental, unresolved mathematical and structural risks specific to these novel derivative designs.

### Approved Open Questions
- Conditional Probability Denominator Instability: This is a critical failure mode for this specific derivative variant, and without a standardized approach, implementations will be highly unstable during periods of low probability for the conditioning event.
- Event-Basket Rebalancing Conventions: The absence of standard rebalancing conventions for these instruments makes them difficult to benchmark and creates ambiguity in how traders should hedge and how venues should structure margin.

## Links

- [Abstract](https://arxiv.org/abs/2605.10428)
- [PDF](https://arxiv.org/pdf/2605.10428)

