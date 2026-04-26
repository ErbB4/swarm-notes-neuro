---
# CSL-compatible fields
title: "VLTI-GRAVITY measurements of cool evolved stars: II. Pulsation properties and mass-loss process of the Mira star R Car and the red supergiant VX Sgr"
author:
  - literal: "D. Jadlovský"
  - literal: "M. Wittkowski"
  - literal: "A. Chiavassa"
  - literal: "K. Kravchenko"
  - literal: "B. Freytag"
  - literal: "S. Höfner"
  - literal: "J. Krtička"
  - literal: "C. Paladini"
  - literal: "G. Rau"
  - literal: "M. Brož"
  - literal: "T. Granzer"
  - literal: "M. Weber"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21621"

# Custom fields
paper_id: "2604.21621"
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
processed_at: "2026-04-26T05:53:03Z"
created_at: "2026-04-26T05:53:03Z"
---

# VLTI-GRAVITY measurements of cool evolved stars: II. Pulsation properties and mass-loss process of the Mira star R Car and the red supergiant VX Sgr

**Authors**: D. Jadlovský, M. Wittkowski, A. Chiavassa, K. Kravchenko, B. Freytag, S. Höfner, J. Krtička, C. Paladini, G. Rau, M. Brož, T. Granzer, M. Weber
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21621](https://arxiv.org/abs/2604.21621)

## Summary

This study presents a 7-year multi-epoch VLTI-GRAVITY time-series analysis of two evolved stars, the AGB star R Car and the red supergiant VX Sgr. By tracking the time-dependent angular diameter and atmospheric layers, the authors demonstrate that Mira stars exhibit stable fundamental mode pulsations correlated with steady mass loss. In contrast, the RSG VX Sgr shows evidence of intermittent, extreme mass-loss events linked to transitions in pulsation mode and propagating atmospheric shocks, providing a new observational framework for understanding RSG mass-loss processes.

## Key Contributions

- Constructed the largest VLTI time-series dataset to date for evolved stars, comprising 54 snapshots of R Car and VX Sgr over 7 years.
- Quantified the relationship between photospheric radius variability and light curve phase shifts, identifying distinct pulsation behaviors for Miras and RSGs.
- Identified that RSG mass-loss is likely driven by extreme, stochastic events triggered by pulsation mode shifts, contrasting with the steady pulsation-driven mass loss observed in Miras.

## Open Questions & Future Work

- [[rsg-mass-loss-initiation-models]]

## Archivist Review

The paper contributes significant astronomical insights into stellar evolution but does not propose generalizable ML mechanisms or architectures. The open question regarding mass-loss initiation is approved as it addresses a fundamental limitation in the physics-informed modeling of time-series data in high-variance, non-stationary astrophysical contexts.

### Approved Open Questions
- RSG mass-loss initiation mechanisms: Addressing this is critical for understanding the final evolutionary stages of massive stars and their contribution to the chemical enrichment of the interstellar medium, as the current mismatch between observations and models limits the ability to predict pre-supernova mass loss.

### Rejected Candidates
- [dataset] VLTI-GRAVITY time-series dataset (`vlti-gravity-time-series-dataset`) - not_reusable: This is a domain-specific observational dataset rather than an ML benchmark dataset; it is too narrow for general forecasting methods.

## Links

- [Abstract](https://arxiv.org/abs/2604.21621)
- [PDF](https://arxiv.org/pdf/2604.21621)

