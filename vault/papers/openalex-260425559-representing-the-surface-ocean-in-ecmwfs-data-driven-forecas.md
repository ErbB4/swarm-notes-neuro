---
# CSL-compatible fields
title: "Representing the Surface Ocean in ECMWF's data-driven forecasting system AIFS"
author:
  - literal: "Sara Hahner"
  - literal: "Lorenzo Zampieri"
  - literal: "Jean‐Raymond Bidlot"
  - literal: "Philip Browne"
  - literal: "Matthew Chantry"
  - literal: "Mariana C. A. Clare"
  - literal: "Harrison Cook"
  - literal: "Peter Dueben"
  - literal: "Rachel Furner"
  - literal: "Sarah Keeley"
  - literal: "Josh Kousal"
  - literal: "Simon Lang"
  - literal: "Christian Lessig"
  - literal: "Gert Mertes"
  - literal: "Kristian Mogensen"
  - literal: "Gabriel Moldovan"
  - literal: "Charles Pelletier"
  - literal: "Florian Pinault"
  - literal: "Ana Prieto Nemesio"
  - literal: "Baudouin Raoult"
  - literal: "Irina Sandu"
  - literal: "Mario Santa Cruz"
  - literal: "Jakob Schloer"
  - literal: "Steffen Tietsche"
  - literal: "Hao Zuo"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25559"

# Custom fields
paper_id: "2604.25559"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "earth-system-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T06:04:36Z"
created_at: "2026-05-01T06:04:36Z"
---

# Representing the Surface Ocean in ECMWF's data-driven forecasting system AIFS

**Authors**: Sara Hahner, Lorenzo Zampieri, Jean‐Raymond Bidlot, Philip Browne, Matthew Chantry, Mariana C. A. Clare, Harrison Cook, Peter Dueben, Rachel Furner, Sarah Keeley, Josh Kousal, Simon Lang, Christian Lessig, Gert Mertes, Kristian Mogensen, Gabriel Moldovan, Charles Pelletier, Florian Pinault, Ana Prieto Nemesio, Baudouin Raoult, Irina Sandu, Mario Santa Cruz, Jakob Schloer, Steffen Tietsche, Hao Zuo
**Date**: 2026-04-28
**Paper ID**: [openalex:2604.25559](https://arxiv.org/abs/2604.25559)

## Summary

This paper presents a coupled, data-driven forecasting system that extends ECMWF's AIFS by integrating atmosphere, surface ocean, wave, and sea ice components into a single joint model. By abandoning the traditional split between atmospheric and marine numerical models, the system learns complex, cross-component relationships directly from data. The proposed architecture demonstrates robust physical consistency and yields a significant one-day improvement in medium-range forecast skill for marine variables compared to existing physics-based benchmarks. The work provides a blueprint for building integrated, data-driven Earth system models that handle multi-scale temporal dynamics and land-masking constraints.

## Key Contributions

- Extends the AIFS (ECMWF's data-driven model) to a jointly learned atmosphere-ocean coupled forecasting system.
- Demonstrates approximately one day of improved forecast skill for most marine variables at medium-range lead times over traditional physics-based models.
- Introduces a component-agnostic joint training approach that learns cross-component correlations directly from unified Earth system data.
- Addresses core ML-for-weather design challenges including missing values over land, multi-scale dynamics, and loss-scaling strategies for physical realism.

## Open Questions & Future Work

- [[ml-model-trend-representation-bottleneck]]
- [[dataset-inconsistency-joint-modeling-bottleneck]]

## Archivist Review

The paper introduces a significant shift in data-driven Earth system modeling by advocating for a component-agnostic joint training approach rather than modular coupling. The identified open questions regarding climate trend representation and cross-dataset inconsistencies are fundamental bottlenecks for this emerging paradigm. I have rejected all concept candidates as they were either too specific to the implementation of AIFS or lacked the required generality for long-term vault retention.

### Approved Open Questions
- ML-model trend representation bottleneck: Addressing this is critical for the long-term reliability of data-driven Earth system models, as failure to represent trends correctly limits their utility for climate change studies and long-term projection.
- Dataset inconsistency joint-modeling bottleneck: This bottleneck prevents the seamless scaling of data-driven Earth system models and directly impacts the forecast accuracy of crucial near-surface interactions.

## Links

- [Abstract](https://arxiv.org/abs/2604.25559)
- [PDF](https://arxiv.org/pdf/2604.25559)

