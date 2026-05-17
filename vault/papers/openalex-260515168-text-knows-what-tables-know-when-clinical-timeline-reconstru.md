---
# CSL-compatible fields
title: "Text Knows What, Tables Know When: Clinical Timeline Reconstruction via Retrieval-Augmented Multimodal Alignment"
author:
  - literal: "Sayantan Kumar"
  - literal: "Shahriar Noroozizadeh"
  - literal: "Juyong Kim"
  - literal: "Jeremy C. Weiss"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15168"

# Custom fields
paper_id: "2605.15168"
paper_source: "openalex"
domain: "nlp"
tags:
  - "clinical-prediction"
  - "multimodal-learning"
  - "retrieval-augmented-generation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "retrieval-augmented-multimodal-alignment"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T06:09:24Z"
created_at: "2026-05-17T06:09:24Z"
---

# Text Knows What, Tables Know When: Clinical Timeline Reconstruction via Retrieval-Augmented Multimodal Alignment

**Authors**: Sayantan Kumar, Shahriar Noroozizadeh, Juyong Kim, Jeremy C. Weiss
**Date**: 2026-05-14
**Paper ID**: [openalex:2605.15168](https://arxiv.org/abs/2605.15168)

## Summary

This paper presents a retrieval-augmented multimodal alignment framework designed to reconstruct precise clinical timelines by combining unstructured narratives with structured EHR data. The approach utilizes a graph-based, multi-step process that builds a temporal scaffold from narrative anchor events and calibrates them using retrieved structured tabular records as temporal evidence. Experiments on the i2m4 benchmark demonstrate that integrating these modalities significantly enhances absolute timestamp accuracy and temporal concordance over text-only baselines.

## Key Contributions

- Introduces a graph-based, retrieval-augmented multimodal alignment framework for precise clinical timeline reconstruction.
- Achieves superior absolute timestamp accuracy (AULTC) and improved temporal concordance compared to unimodal text-only approaches on the i2m4 benchmark.
- Quantifies the clinical data gap, revealing that 34.8% of text-derived events are missing from structured tabular records.

## Open Questions & Future Work

- [[generalization-of-clinical-timeline-reconstruction]]

## Key Concepts

- [[retrieval-augmented-multimodal-alignment]]: A graph-based framework for refining clinical event timelines by using structured EHR data as temporal anchors for events extracted from unstructured text.

## Archivist Review

I approved the core retrieval-augmented multimodal alignment concept as a novel mechanism for longitudinal clinical data integration. The open question regarding its generalization was approved because the current reliance on sepsis-specific, limited-scale benchmarks is a known obstacle in the field. Other items were rejected for being domain-specific benchmarks or overly generic future work.

### Approved Concepts
- Retrieval-augmented multimodal alignment: It serves as a novel paradigm for synchronizing heterogeneous data sources (narratives and structured EHRs) to enhance temporal fidelity.

### Approved Open Questions
- Generalization of Clinical Timeline Reconstruction: Scaling beyond constrained, sepsis-specific benchmarks is essential to validate whether the proposed multimodal scaffold is a robust solution for heterogeneous patient trajectories.

### Rejected Candidates
- [dataset] i2m4 benchmark (`i2m4-benchmark`) - not_reusable: Routine benchmark specific to the paper that does not justify a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2605.15168)
- [PDF](https://arxiv.org/pdf/2605.15168)

