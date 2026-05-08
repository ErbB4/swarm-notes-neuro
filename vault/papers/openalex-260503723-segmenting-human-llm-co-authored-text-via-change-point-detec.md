---
# CSL-compatible fields
title: "Segmenting Human-LLM Co-authored Text via Change Point Detection"
author:
  - literal: "Mengchu Li"
  - literal: "Jin Zhu"
  - literal: "Jinglai Li"
  - literal: "Chengchun Shi"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03723"

# Custom fields
paper_id: "2605.03723"
paper_source: "openalex"
domain: "nlp"
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
processed_at: "2026-05-08T05:44:30Z"
created_at: "2026-05-08T05:44:30Z"
---

# Segmenting Human-LLM Co-authored Text via Change Point Detection

**Authors**: Mengchu Li, Jin Zhu, Jinglai Li, Chengchun Shi
**Date**: 2026-05-05
**Paper ID**: [openalex:2605.03723](https://arxiv.org/abs/2605.03723)

## Summary

This paper addresses the challenge of localizing human-written and LLM-generated segments within co-authored documents. By modeling the text authorship as a sequence with varying detection scores, the authors reframe the task as a change point detection problem. They propose two robust algorithms—a weighted version and a generalized version—to handle heterogeneous score distributions and demonstrate their theoretical minimax optimality and empirical superiority over baseline methods.

## Key Contributions

- Formulates the task of segmenting human-LLM co-authored text as a change point detection problem in time-series analysis.
- Develops weighted and generalized change point detection algorithms specifically designed to account for heterogeneous score variability in LLM text detection.
- Provides theoretical proof establishing the minimax optimality of the proposed segmentation procedure.

## Open Questions & Future Work

- [[co-authored-text-segmentation-dependency-bottleneck]]

## Archivist Review

The paper provides a statistical framework for text segmentation by reframing it as a change point detection problem. I have approved the open question regarding the bottleneck caused by the independence assumption, as it highlights a significant limitation in applying classical change point models to linguistically dependent co-authored sequences. The proposed algorithms were rejected as they represent specific methodological adaptations rather than broadly applicable novel mechanisms.

### Approved Open Questions
- Co-authored Text Segmentation Dependency Bottleneck: The assumption of independence between sentence-level scores is a simplification that limits the applicability of current change point models in complex, cohesive prose, which is the primary domain of LLM-human co-authoring. Addressing these dependencies is crucial for improving boundary detection accuracy in real-world writing tasks.

### Rejected Candidates
- [concept] Formulating authorship segmentation as change point detection (`formulation-of-authorship-segmentation-as-change-point-detection`) - not_novel: Reframing a task using an existing statistical method is an application rather than a new reusable mechanism.
- [concept] Weighted and generalized change point detection algorithms (`weighted-and-generalized-change-point-detection-algorithms`) - subcomponent_of_broader_mechanism: These are specific algorithmic variations applied to a specific task, better categorized as methodological adjustments than a permanent concept.

## Links

- [Abstract](https://arxiv.org/abs/2605.03723)
- [PDF](https://arxiv.org/pdf/2605.03723)

