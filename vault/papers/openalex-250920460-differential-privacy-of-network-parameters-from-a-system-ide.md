---
# CSL-compatible fields
title: "Differential Privacy of Network Parameters From a System Identification Perspective"
author:
  - literal: "Andrew R. Campbell"
  - literal: "Anna Scaglione"
  - literal: "Hang Liu"
  - literal: "Victor Daniel Elvira"
  - literal: "Sean Peisert"
  - literal: "Daniel Arnold"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.20460"

# Custom fields
paper_id: "2509.20460"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "privacy"
  - "graph-theory"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:52:18Z"
created_at: "2026-04-24T05:52:18Z"
---

# Differential Privacy of Network Parameters From a System Identification Perspective

**Authors**: Andrew R. Campbell, Anna Scaglione, Hang Liu, Victor Daniel Elvira, Sean Peisert, Daniel Arnold
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.20460](https://arxiv.org/abs/2509.20460)

## Summary

This paper addresses the challenge of securing network topology information in cyber-physical system simulations against system identification (SI) attacks. By modeling observations as outputs of a graph filter driven by differentially private nodal excitations, the authors derive a formal relationship between privacy guarantees and the spectral properties of the system. The analysis shows that both the smoothness of the filter and the conditioning of the noise covariance are fundamental determinants of the privacy bound for inferring the graph shift operator. This work provides a rigorous mathematical foundation for balancing privacy requirements with data utility in networked time-series sharing.

## Key Contributions

- Proposes a theoretical framework for protecting Graph Shift Operators (GSO) against system identification attacks in cyber-physical system simulations.
- Establishes a quantitative link between (ε, δ)-differential privacy bounds and the spectral characteristics of graph filters and noise covariance.
- Demonstrates that smooth graph filters and low-condition-number noise covariance increase privacy bounds for network parameter identification.

## Open Questions & Future Work

- [[optimal-noise-covariance-design-gso-privacy]]

## Archivist Review

I approved the open question regarding optimal noise covariance design as it addresses a fundamental trade-off between privacy guarantees and signal utility in networked systems. The concept of a privacy framework was rejected because it represents a theoretical analysis of existing mathematical components rather than an independently reusable method or architecture.

### Approved Open Questions
- Optimal Noise Covariance Design: This is a fundamental challenge in balancing privacy utility and data statistical properties, as current approaches identify the potential for 'privacy for free' but note the restrictive nature of the required noise structure in real-world scenarios.

### Rejected Candidates
- [concept] Graph Shift Operator Privacy Framework (`graph-shift-operator-privacy-framework`) - not_novel: The framework combines existing concepts of Differential Privacy and System Identification and does not propose a specific, named algorithmic component that would be referenced independently in future research.

## Links

- [Abstract](https://arxiv.org/abs/2509.20460)
- [PDF](https://arxiv.org/pdf/2509.20460)

