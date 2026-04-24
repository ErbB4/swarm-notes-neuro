---
# CSL-compatible fields
title: "State Forecasting in an Estimation Framework with Surrogate Sensor Modeling"
author:
  - literal: "Sriram Narayanan"
  - literal: "Mohamed Naveed Gul Mohamed"
  - literal: "Ishan Paranjape"
  - literal: "Indranil Nayak"
  - literal: "Suman Chakravorty"
  - literal: "Mrinal Kumar"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19442"

# Custom fields
paper_id: "2604.19442"
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
processed_at: "2026-04-24T05:51:28Z"
created_at: "2026-04-24T05:51:28Z"
---

# State Forecasting in an Estimation Framework with Surrogate Sensor Modeling

**Authors**: Sriram Narayanan, Mohamed Naveed Gul Mohamed, Ishan Paranjape, Indranil Nayak, Suman Chakravorty, Mrinal Kumar
**Date**: 2026-04-21
**Paper ID**: [openalex:2604.19442](https://arxiv.org/abs/2604.19442)

## Summary

This paper addresses the challenge of state estimation from sparse, partial measurements in aerospace applications, specifically for resident space object tracking. The authors propose a novel framework that bridges physics-based reference models with data-driven surrogate sensor models. By integrating these two paradigms, the framework achieves accurate reconstruction of system dynamics despite limited observability. Empirical validation across multiple datasets confirms the efficacy and robustness of the proposed surrogate-based estimation approach.

## Key Contributions

- Introduced a fusion framework integrating reference dynamics with data-driven surrogate measurement models for state estimation in partial observability settings.
- Demonstrated robust system dynamics reconstruction from sparse radar and optical range/bearing measurements common in space situational awareness.
- Presented an initial consistency analysis of surrogate sensor modeling to validate framework robustness against incomplete observational data.

## Open Questions & Future Work

- [[double-dipping-bias-hybrid-estimation]]

## Archivist Review

I have approved the open question regarding double-dipping bias in hybrid estimation systems, as it addresses a fundamental methodological challenge in the increasingly important field of physics-informed machine learning. I rejected the concept candidate "surrogate sensor modeling" because the technique itself is too broad and standard to be a distinct, vault-worthy research concept without a more specific algorithmic innovation.

### Approved Open Questions
- Double dipping bias in hybrid estimation: This is crucial for the statistical integrity of hybrid data-driven/physics-based estimation systems, where failing to address circular dependency can lead to overconfident or biased state estimates.

### Rejected Candidates
- [concept] Surrogate sensor modeling (`surrogate-sensor-modeling`) - not_novel: Surrogate modeling is a well-established technique across many fields; without a more specific methodological innovation, this remains a standard application rather than a reusable core concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.19442)
- [PDF](https://arxiv.org/pdf/2604.19442)

