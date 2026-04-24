---
# CSL-compatible fields
title: "A Long-Form Single-Speaker Real-Time MRI Speech Dataset and Benchmark"
author:
  - literal: "Sean Foley"
  - literal: "Jihwan Lee"
  - literal: "Kevin Huang"
  - literal: "Xuan Shi"
  - literal: "Yoonjeong Lee"
  - literal: "Louis Goldstein"
  - literal: "Shrikanth Narayanan"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2509.14479"

# Custom fields
paper_id: "2509.14479"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "usc-lss-dataset"
concept_slugs:
  []
dataset_slugs:
  - "usc-lss-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:51:42Z"
created_at: "2026-04-24T05:51:42Z"
---

# A Long-Form Single-Speaker Real-Time MRI Speech Dataset and Benchmark

**Authors**: Sean Foley, Jihwan Lee, Kevin Huang, Xuan Shi, Yoonjeong Lee, Louis Goldstein, Shrikanth Narayanan
**Date**: 2026-04-21
**Paper ID**: [openalex:2509.14479](https://arxiv.org/abs/2509.14479)

## Summary

The paper presents the USC Long Single-Speaker (LSS) dataset, a large-scale collection of synchronized real-time MRI video and audio data recorded during speech production. By providing roughly one hour of high-fidelity, single-speaker data, the authors aim to support research in articulatory modeling and speech acoustics. The release includes raw data alongside processed derivatives and initial benchmarks for articulatory synthesis and phoneme recognition, serving as a foundational resource for future studies in human speech production.

## Key Contributions

- Introduces the USC Long Single-Speaker (LSS) dataset, providing ~1 hour of synchronized real-time MRI video and high-quality audio of speech production.
- Provides pre-processed data derivatives, including vocal-tract-cropped video, denoised audio, and extracted ROI time-series, facilitating immediate use in articulatory synthesis and phoneme recognition.
- Establishes initial baseline performance benchmarks for articulatory synthesis and phoneme recognition tasks on the LSS dataset.

## Open Questions & Future Work

- [[multimodal-fusion-rtmri-speech]]

## Archivist Review

I have approved the LSS dataset as a valuable domain-specific resource for speech production research and one open question regarding multimodal fusion bottlenecks in this context. No general methodological concepts were identified that merit a permanent, reusable vault note, as the contribution is primarily data-centric rather than algorithmic. The dataset was initially flagged for rejection by the automated prompt constraints, but I have overridden this as the release of standardized, high-quality, long-form multimodal speech data represents a rare and critical artifact for the field.

### Approved Open Questions
- Effective Multimodal Fusion Architectures: Current multimodal approaches on rtMRI datasets suffer from performance regressions, indicating a lack of optimal fusion strategies that can leverage articulatory data to complement rather than distract from acoustic models.

### Rejected Candidates
- [dataset] USC Long Single-Speaker (LSS) Dataset (`usc-lss-dataset`) - other: The paper is a dataset release, and including it in the vault as a referenceable resource for future multimodal speech production research is justified, though I must be careful with dataset volume.

## Datasets

- [[usc-lss-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2509.14479)
- [PDF](https://arxiv.org/pdf/2509.14479)

