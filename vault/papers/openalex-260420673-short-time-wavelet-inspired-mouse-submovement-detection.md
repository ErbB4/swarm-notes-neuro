---
# CSL-compatible fields
title: "Short-time, Wavelet-inspired Mouse Submovement Detection"
author:
  - literal: "Auejin Ham"
  - literal: "Ben Boudaoud"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20673"

# Custom fields
paper_id: "2604.20673"
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
processed_at: "2026-04-25T05:38:30Z"
created_at: "2026-04-25T05:38:30Z"
---

# Short-time, Wavelet-inspired Mouse Submovement Detection

**Authors**: Auejin Ham, Ben Boudaoud
**Date**: 2026-04-22
**Paper ID**: [openalex:2604.20673](https://arxiv.org/abs/2604.20673)

## Summary

This paper addresses the difficulty of decomposing overlapping ballistic submovements within human motor interaction data. The authors propose a wavelet-inspired segmentation technique specifically designed to identify these components from 1D speed time series. To enhance fitting accuracy, the method incorporates a self-weighted loss refinement step, effectively addressing limitations inherent in simpler wavelet-based approaches. Evaluation against standard segmentation baselines confirms the utility of this method for processing complex, high-frequency motor data.

## Key Contributions

- Proposes a wavelet-inspired method for detecting and parameterizing submovements in 1D speed time series.
- Introduces a self-weighted loss refinement mechanism to mitigate fitting errors common in standard wavelet-based motion segmentation.
- Validates the approach against dual-threshold and 1D persistence segmentation techniques using synthetic egocentric movement data with known ground truth.

## Open Questions & Future Work

- [[robust-submovement-decomposition-optimization]]

## Archivist Review

I have approved the open question regarding robust submovement decomposition because it represents a clear, long-standing bottleneck in motor control analysis and human-computer interaction research. The proposed concepts were rejected because they are either minor implementation variations or too highly specialized to the domain of mouse-tracking to be considered reusable primitives in the broader time-series literature.

### Approved Open Questions
- Robust Submovement Decomposition Optimization: Improving submovement decomposition is critical for accurately characterizing human motor control strategies. Existing threshold-based or iterative methods often fail to account for high degrees of overlap or result in spurious detections, limiting their reliability for fine-grained behavioral analysis.

### Rejected Candidates
- [concept] Wavelet-inspired Submovement Detection (`wavelet-inspired-submovement-detection`) - not_reusable: The method is too domain-specific and narrow to warrant a general-purpose concept note, functioning more as an application of existing wavelet transforms to motion tracking.
- [concept] Self-weighted Loss Refinement (`self-weighted-loss-refinement`) - subcomponent_of_broader_mechanism: This is a standard implementation detail for loss functions rather than a novel, reusable algorithmic concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.20673)
- [PDF](https://arxiv.org/pdf/2604.20673)

