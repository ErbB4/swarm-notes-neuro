---
# CSL-compatible fields
title: "Recurrence analysis of quantum many-body dynamics"
author:
  - literal: "Tomasz Szołdra"
  - literal: "Matheus S. Palmero"
  - literal: "Peter Schmelcher"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18446"

# Custom fields
paper_id: "2604.18446"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-analysis"
  - "quantum-many-body-dynamics"
architectures:
  []
datasets:
  []
concept_slugs:
  - "recurrence-quantification-analysis-quantum-dynamics"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:48:21Z"
created_at: "2026-04-23T05:48:21Z"
---

# Recurrence analysis of quantum many-body dynamics

**Authors**: Tomasz Szołdra, Matheus S. Palmero, Peter Schmelcher
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18446](https://arxiv.org/abs/2604.18446)

## Summary

This paper adapts recurrence analysis—a traditional tool for nonlinear dynamical systems—to the study of out-of-equilibrium quantum many-body dynamics. By generating recurrence plots from correlation observables and utilizing recurrence quantification analysis, the authors successfully characterize complex temporal behavior during quantum quenches. Applied to the 1D transverse-field Ising model, the method enables unsupervised detection of quantum phase transitions by identifying qualitative and numerical changes in correlation structures.

## Key Contributions

- Introduces recurrence analysis as a diagnostic tool for characterizing out-of-equilibrium quantum many-body systems.
- Demonstrates that recurrence quantification analysis can autonomously detect critical points in quantum phase transitions using two-site correlation dynamics.
- Validates the framework on the 1D transverse-field Ising model, showing distinct recurrence patterns for paramagnetic and ferromagnetic phases.

## Open Questions & Future Work

- [[recurrence-analysis-mbl-detection]]
- [[recurrence-analysis-scarring-detection]]

## Key Concepts

- [[recurrence-quantification-analysis-quantum-dynamics]]: A nonlinear time-series analysis framework used to extract numerical descriptors from quantum many-body dynamics for phase transition detection.

## Archivist Review

The paper successfully bridges nonlinear time-series analysis (recurrence plots/quantification) with quantum many-body dynamics, providing a diagnostic tool that is distinct and reusable for phase transition analysis. I approved two open questions that specifically target the application of this method to distinct quantum phenomena (MBL and scarring), as these represent clear, non-trivial research directions that generalize the paper's contribution beyond the Ising model.

### Approved Concepts
- Recurrence Quantification Analysis for Quantum Dynamics: The paper adapts nonlinear time-series analysis tools to identify phase transitions in quantum systems without prior model knowledge.

### Approved Open Questions
- Recurrence analysis for MBL: Determining whether recurrence quantification can identify critical disorder strengths without extensive system-size scaling would provide a computationally efficient, unsupervised diagnostic for ergodicity breaking in quantum dynamics.
- Recurrence analysis for scarring: Scarred dynamics are often hidden in complex high-energy spectra; establishing a robust, visual, and quantitative tool to isolate and characterize these signatures is essential for advancing research on constrained quantum dynamics.

## Links

- [Abstract](https://arxiv.org/abs/2604.18446)
- [PDF](https://arxiv.org/pdf/2604.18446)

