---
# CSL-compatible fields
title: "An analytical approach to calculating stationary PDFs for reflected random walks with an application to BESS-based ramp-rate control"
author:
  - literal: "Carlos Colchero"
  - literal: "Diego Jiménez-Arreguín"
  - literal: "Álvaro Herrera"
  - literal: "Jorge E. Pérez-García"
  - literal: "Oliver Probst"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12405"

# Custom fields
paper_id: "2605.12405"
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
processed_at: "2026-05-15T06:15:43Z"
created_at: "2026-05-15T06:15:43Z"
---

# An analytical approach to calculating stationary PDFs for reflected random walks with an application to BESS-based ramp-rate control

**Authors**: Carlos Colchero, Diego Jiménez-Arreguín, Álvaro Herrera, Jorge E. Pérez-García, Oliver Probst
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12405](https://arxiv.org/abs/2605.12405)

## Summary

This paper addresses the problem of determining stationary probability density functions (PDFs) for reflected random walks, which are used to model the behavior of battery energy storage systems (BESS). By reformulating the problem as a Fredholm integral equation of the second kind, the authors derive an analytical solution via Neumann series. This mathematical framework provides practitioners with efficient design rules for inverter sizing, offering a performance advantage over purely numerical Nystrom methods or algorithmic simulations for wind and solar ramp-rate control.

## Key Contributions

- Derives a rigorous Wiener-Hopf-type integral equation for the stationary PDF of a reflected random walk.
- Develops a closed-form analytical solution using Neumann series for BESS power PDF estimation.
- Provides simplified, truncated analytical design rules for inverter sizing in renewable energy ramp-rate control.

## Open Questions & Future Work

- [[bess-sizing-complex-dynamics-bottleneck]]
- [[bess-energy-capacity-sizing-bottleneck]]

## Archivist Review

The paper contributes a specialized analytical approach to BESS sizing via reflected random walks, but this is a domain-specific mathematical technique rather than a broad, reusable machine learning concept. I have approved two open questions that define the current limitations in moving from stylized analytical models to realistic power system dynamics and total storage capacity planning.

### Approved Open Questions
- BESS sizing complex dynamics bottleneck: Bridging the gap between idealized analytical models and field operating conditions is necessary for developing reliable, science-based sizing standards for power systems.
- BESS energy capacity sizing bottleneck: Energy capacity is a fundamental design dimension limiting the duration of support during prolonged ramp events, yet it remains analytically under-addressed compared to power capacity.

## Links

- [Abstract](https://arxiv.org/abs/2605.12405)
- [PDF](https://arxiv.org/pdf/2605.12405)

