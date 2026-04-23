---
# CSL-compatible fields
title: "EAST: Early Action Prediction Sampling Strategy with Token Masking"
author:
  - literal: "Iva Sović"
  - literal: "Ivan Martinović"
  - literal: "Marin Oršić"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18367"

# Custom fields
paper_id: "2604.18367"
paper_source: "openalex"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "early-action-prediction-sampling-strategy"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:49:06Z"
created_at: "2026-04-23T05:49:06Z"
---

# EAST: Early Action Prediction Sampling Strategy with Token Masking

**Authors**: Iva Sović, Ivan Martinović, Marin Oršić
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18367](https://arxiv.org/abs/2604.18367)

## Summary

EAST is an efficient framework for early action prediction that addresses the challenge of limited visual evidence in incomplete video sequences. By using a randomized training strategy to sample the division between observed and unobserved frames, the model achieves robust performance across diverse observation ratios. Additionally, the framework incorporates a token masking mechanism to enhance scalability and employs joint learning with future oracle representations to boost accuracy. Empirical results on NTU60, SSv2, and UCF101 demonstrate that EAST significantly outperforms existing methods in both efficiency and predictive accuracy.

## Key Contributions

- Introduces EAST, a framework for early action prediction that uses a randomized temporal split-point sampling strategy.
- Demonstrates that joint learning on observed and oracle (future) representations significantly improves encoder performance.
- Proposes a token masking procedure that reduces memory usage by 50% and improves training speed by 2x.
- Sets a new state-of-the-art on NTU60, SSv2, and UCF101, outperforming prior work by up to 10.1 percentage points.

## Open Questions & Future Work

- [[unified-action-prediction-anticipation]]
- [[streaming-inference-limitations]]

## Key Concepts

- [[early-action-prediction-sampling-strategy]]: A training strategy that samples varying observation-future split points to make models robust to different test-time observation ratios.

## Archivist Review

The approved concept addresses the core challenge of variable observation ratios in early prediction. The open questions capture fundamental bottlenecks in unification and streaming deployment. Other items like datasets were rejected as they are standard benchmarks, and the token masking was deemed a minor implementation detail compared to the main sampling strategy.

### Approved Concepts
- Early Action Prediction Sampling Strategy: It is the central methodological contribution for handling incomplete temporal video observations.

### Approved Open Questions
- Unified Action Prediction Framework: Bridging these subfields could lead to more robust and versatile video understanding systems that handle diverse temporal horizons consistently.
- Streaming Inference Challenges: Developing streaming-capable architectures is essential for real-world deployment in safety-critical, time-sensitive applications.

### Rejected Candidates
- [concept] Token Masking Procedure (`token-masking-procedure`) - subcomponent_of_broader_mechanism: This is a sub-component optimization rather than a core conceptual framework for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.18367)
- [PDF](https://arxiv.org/pdf/2604.18367)

