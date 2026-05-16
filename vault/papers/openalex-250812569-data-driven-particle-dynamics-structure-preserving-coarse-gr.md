---
# CSL-compatible fields
title: "Data-driven particle dynamics: Structure-preserving coarse-graining for emergent behavior in nonequilibrium systems"
author:
  - literal: "Quercus Hernández"
  - literal: "Max Win"
  - literal: "Thomas C. O’Connor"
  - literal: "Paulo E. Arratia"
  - literal: "Nathaniel Trask"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2508.12569"

# Custom fields
paper_id: "2508.12569"
paper_source: "openalex"
domain: "physics-informed-ml"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "metriplectic-bracket-ml"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:02:52Z"
created_at: "2026-05-16T06:02:52Z"
---

# Data-driven particle dynamics: Structure-preserving coarse-graining for emergent behavior in nonequilibrium systems

**Authors**: Quercus Hernández, Max Win, Thomas C. O’Connor, Paulo E. Arratia, Nathaniel Trask
**Date**: 2026-05-13
**Paper ID**: [openalex:2508.12569](https://arxiv.org/abs/2508.12569)

## Summary

This paper addresses the difficulty of linking small-scale particle dynamics to emergent bulk physics by proposing a coarse-graining framework based on the metriplectic bracket formalism. By design, the approach ensures that learned models satisfy fundamental constraints, including the first and second laws of thermodynamics, momentum conservation, and fluctuation-dissipation balance. The authors further introduce a self-supervised learning technique to extract emergent structural variables and validate the framework on complex colloidal systems and polymer simulations.

## Key Contributions

- Introduces a metriplectic bracket-based machine learning framework that embeds discrete laws of thermodynamics and conservation of momentum into coarse-grained particle dynamics.
- Develops a self-supervised learning strategy to identify emergent structural state variables in the absence of explicit labels.
- Demonstrates the framework's ability to preserve nonequilibrium statistics in star polymer coarse-graining and capture stochastic dynamics in colloidal suspensions from video.

## Key Concepts

- [[metriplectic-bracket-ml]]: A framework for learning coarse-grained dynamical systems that enforces thermodynamic consistency via metriplectic brackets.

## Archivist Review

The paper introduces a principled way to incorporate thermodynamic constraints into neural dynamics via metriplectic brackets, which is a significant contribution to scientific ML. I have approved this concept due to its broad applicability to multiscale systems and nonequilibrium physics. No other candidates were provided or identified as meeting the criteria.

### Approved Concepts
- Metriplectic bracket machine learning: Provides a rigorous way to embed physical constraints (thermodynamics, conservation laws) directly into neural network dynamics.

## Links

- [Abstract](https://arxiv.org/abs/2508.12569)
- [PDF](https://arxiv.org/pdf/2508.12569)

