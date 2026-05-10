---
# CSL-compatible fields
title: "Modeling of Coronal Mass Ejection Originated from a Sheared Arcade of Realistic Active-Region Scale and Its Propagation in the Heliosphere: Methodology"
author:
  - literal: "Chaowei Jiang"
  - literal: "Xueshang Feng"
  - literal: "Liping Yang"
  - literal: "Huichao Li"
  - literal: "Jinhan Guo"
  - literal: "Pingbing Zuo"
  - literal: "Yi Wang"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05883"

# Custom fields
paper_id: "2605.05883"
paper_source: "openalex"
domain: "physics"
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
processed_at: "2026-05-10T06:09:00Z"
created_at: "2026-05-10T06:09:00Z"
---

# Modeling of Coronal Mass Ejection Originated from a Sheared Arcade of Realistic Active-Region Scale and Its Propagation in the Heliosphere: Methodology

**Authors**: Chaowei Jiang, Xueshang Feng, Liping Yang, Huichao Li, Jinhan Guo, Pingbing Zuo, Yi Wang
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05883](https://arxiv.org/abs/2605.05883)

## Summary

This paper presents an end-to-end magnetohydrodynamic (MHD) simulation methodology for coronal mass ejections (CMEs) that spans from active region scales on the solar surface to heliospheric propagation at 1.5 au. By integrating block-structured adaptive mesh refinement with a semi-relativistic Boris correction, the model achieves high resolution in the low corona while maintaining computational efficiency for realistic magnetic field strengths. The approach successfully captures the full lifecycle of a CME, including energy buildup, eruption initiation via magnetic reconnection, and shock formation, with a 1 au arrival time predictable within a two-day lead time.

## Key Contributions

- Developed an end-to-end magnetohydrodynamic (MHD) modeling framework coupling three nested simulations from the solar surface to 1.5 au.
- Implemented a block-structured adaptive mesh refinement (AMR) scheme enabling 700 km resolution in the low corona with fewer than 10^8 grid cells.
- Introduced a semi-relativistic Boris correction and relativistic mass-density factor to handle 10^3 G magnetic fields without requiring prohibitively small time steps.

## Open Questions & Future Work

- [[realistic-thermodynamics-solar-wind-modeling]]
- [[data-driven-cme-initiation-boundary-conditions]]

## Archivist Review

The paper focuses on specialized numerical magnetohydrodynamic simulations for solar physics, which fall outside the primary scope of the TimeSeriesSkill vault's interest in forecasting methodologies and temporal inductive biases. While the technical numerical corrections are impressive, they are highly domain-specific to plasma physics rather than generalizable forecasting primitives. I have approved two open questions that highlight the broader challenge of integrating realistic physical constraints and data-driven inputs into large-scale forecasting systems.

### Approved Open Questions
- Improved Solar Wind Thermodynamics: Thermodynamics is crucial for correctly modeling solar wind speed, density, and temperature profiles, which significantly influence the propagation speed and morphological evolution of coronal mass ejections in the heliosphere.
- Data-Driven CME Initiation Modeling: Data-driven boundary conditions are essential for moving from generic mechanism studies to predictive, real-world space weather forecasting based on actual observed solar active regions.

### Rejected Candidates
- [concept] Semi-Relativistic Boris Correction (`semi-relativistic-boris-correction`) - subcomponent_of_broader_mechanism: This is a specific numerical physics technique rather than a broadly reusable modeling architecture or machine learning concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.05883)
- [PDF](https://arxiv.org/pdf/2605.05883)

