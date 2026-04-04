---
# CSL-compatible fields
title: "How Well Do Molecular Dynamics Force Fields Model Peptides? A Systematic Benchmark Across Diverse Folding Behaviors"
author:
  - literal: "Singh, B."
  - literal: "Martinez-Noa, Y."
  - literal: "perez, a."
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://www.biorxiv.org/content/10.1101/2025.07.31.667969"

# Custom fields
paper_id: "10.1101/2025.07.31.667969"
paper_source: "biorxiv"
domain: "molecular-dynamics"
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
skill: "NeuroscienceSkill"
processed_at: "2026-04-04T20:22:34Z"
created_at: "2026-04-04T20:22:34Z"
---

# How Well Do Molecular Dynamics Force Fields Model Peptides? A Systematic Benchmark Across Diverse Folding Behaviors

**Authors**: Singh, B., Martinez-Noa, Y., perez, a.
**Date**: 2026-04-01
**Paper ID**: [biorxiv:10.1101/2025.07.31.667969](https://www.biorxiv.org/content/10.1101/2025.07.31.667969)

## Summary

This study performs a systematic evaluation of twelve fixed-charge force fields to assess their reliability in modeling peptides with varying structural characteristics. By simulating peptides from both folded and extended states, the authors quantify force field biases and their ability to capture conformational dynamics. The findings reveal that no single model excels across the entire spectrum of folding behaviors, highlighting significant challenges in balancing structural order and disorder. This work provides critical benchmarking data and guidelines for future development in peptide-centric molecular dynamics simulations.

## Key Contributions

- Systematic benchmark of twelve popular and emerging fixed-charge force fields against a curated, diverse set of twelve peptides.
- Evaluation protocol using both folded (200 ns) and extended (10 microseconds) simulation states to probe stability and folding behavior.
- Identification of systematic structural biases and limitations in balancing disorder versus secondary structure across current force fields.

## Open Questions & Future Work

- [[balancing-disorder-secondary-structure-md-force-fields]]

## Archivist Review

I approved the open question regarding the difficulty of balancing structural disorder and secondary stability in molecular dynamics force fields, as this represents a fundamental and persistent challenge in computational biophysics. I did not find any concepts in the paper that reached the threshold for standalone vault notes, as the benchmarking approach is highly specific to the force fields evaluated and lacks broad conceptual generalizability. The datasets were rejected as they were described as a 'curated set' without a formal, reusable name or repository, fitting the criteria for routine benchmarking materials rather than novel, named assets.

### Approved Open Questions
- Balancing Disorder and Structure in Force Fields: This is a fundamental limitation in molecular simulations of intrinsically disordered proteins and peptides, impacting drug discovery and structural biology predictions where the native state is highly dynamic.

## Links

- [Abstract](https://www.biorxiv.org/content/10.1101/2025.07.31.667969)
- [PDF](https://www.biorxiv.org/content/10.1101/2025.07.31.667969)

