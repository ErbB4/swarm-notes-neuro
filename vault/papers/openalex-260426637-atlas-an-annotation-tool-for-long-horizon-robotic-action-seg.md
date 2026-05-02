---
# CSL-compatible fields
title: "ATLAS: An Annotation Tool for Long-horizon Robotic Action Segmentation"
author:
  - literal: "Sergej Stanovcic"
  - literal: "Daniel Sliwowski"
  - literal: "Dongheui Lee"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26637"

# Custom fields
paper_id: "2604.26637"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "reassemble"
concept_slugs:
  []
dataset_slugs:
  - "reassemble"
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:49:47Z"
created_at: "2026-05-02T05:49:47Z"
---

# ATLAS: An Annotation Tool for Long-horizon Robotic Action Segmentation

**Authors**: Sergej Stanovcic, Daniel Sliwowski, Dongheui Lee
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26637](https://arxiv.org/abs/2604.26637)

## Summary

The authors introduce ATLAS, a specialized annotation tool designed to streamline the labeling of long-horizon robotic manipulation tasks. By providing time-synchronized visualization of multi-view video and multi-modal proprioceptive time-series data, ATLAS addresses limitations in vision-only annotation tools. Experimental results on contact-rich assembly tasks demonstrate that incorporating proprioceptive signals significantly improves temporal boundary alignment and annotation efficiency. The tool's modular architecture supports standard robotics formats like ROS bags and RLDS, enhancing its utility for diverse robotics research workflows.

## Key Contributions

- Introduces ATLAS, an annotation tool specifically designed for long-horizon robotic demonstrations, integrating multi-view video with time-synchronized proprioceptive signals.
- Reduces average per-action annotation time by at least 6% compared to ELAN, while improving temporal boundary alignment by 2.8% through multi-modal signal visualization.
- Implements a modular dataset abstraction layer supporting ROS bags and RLDS, facilitating extensibility across diverse robotic research formats.

## Open Questions & Future Work

- [[cognitive-load-multimodal-annotation]]

## Archivist Review

I have approved the dataset REASSEMBLE, as it is a specific domain-relevant benchmark cited in the paper, and the open question regarding cognitive load in multimodal annotation, as it addresses a fundamental human-AI interaction bottleneck in high-precision robotics labeling. The tool itself, ATLAS, was rejected as it is a software utility rather than an algorithmic concept.

### Approved Open Questions
- Cognitive load in multimodal annotation: Understanding the trade-off between annotation cognitive load and temporal precision is critical for the development of scalable, human-in-the-loop data labeling systems for complex robotic tasks.

### Rejected Candidates
- [concept] ATLAS Annotation Tool (`atlas-tool`) - paper_local: Annotation tools are typically engineering software artifacts rather than reusable research concepts for the ML vault.

## Datasets

- [[reassemble]]

## Links

- [Abstract](https://arxiv.org/abs/2604.26637)
- [PDF](https://arxiv.org/pdf/2604.26637)

