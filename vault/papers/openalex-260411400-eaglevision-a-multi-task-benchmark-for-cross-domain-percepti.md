---
# CSL-compatible fields
title: "EagleVision: A Multi-Task Benchmark for Cross-Domain Perception in High-Speed Autonomous Racing"
author:
  - literal: "Zakhar Yagudin"
  - literal: "Murad Mebrahtu"
  - literal: "Ren Jin"
  - literal: "Jiaqi Huang"
  - literal: "Yujia Yue"
  - literal: "Dzmitry Tsetserukou"
  - literal: "Jorge Dias"
  - literal: "Majid Khonji"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11400"

# Custom fields
paper_id: "2604.11400"
paper_source: "openalex"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  - "Indy Autonomous Challenge"
  - "A2RL Real competition dataset"
concept_slugs:
  []
dataset_slugs:
  - "indy-autonomous-challenge"
  - "a2rl-real-competition-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:47:35Z"
created_at: "2026-04-16T05:47:35Z"
---

# EagleVision: A Multi-Task Benchmark for Cross-Domain Perception in High-Speed Autonomous Racing

**Authors**: Zakhar Yagudin, Murad Mebrahtu, Ren Jin, Jiaqi Huang, Yujia Yue, Dzmitry Tsetserukou, Jorge Dias, Majid Khonji
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11400](https://arxiv.org/abs/2604.11400)

## Summary

EagleVision is a new multi-task benchmark designed to address perception challenges in high-speed autonomous racing, focusing on 3D object detection and trajectory prediction. The benchmark consolidates diverse data sources, including real-world racing and simulator environments, under a standardized evaluation protocol to assess cross-domain generalization. Empirical results reveal that racing-specific pretraining significantly outperforms urban-only models in high-dynamic scenarios. Furthermore, the findings suggest that motion-distribution coverage is a critical factor for successful trajectory prediction in cross-domain transfer settings.

## Key Contributions

- Introduces EagleVision, a unified LiDAR-based multi-task benchmark for 3D detection and trajectory prediction in high-speed autonomous racing.
- Provides 14,893 frames of newly annotated Indy Autonomous Challenge data, 1,163 A2RL frames, and 12,000 simulator-generated frames.
- Demonstrates that intermediate pretraining on real racing data provides superior transfer to new racing domains compared to simulator-only adaptation.
- Shows that trajectory prediction performance benefits significantly from broad motion-distribution coverage, with Indy-trained models achieving lower FDE (0.947 vs 1.250) on A2RL test sequences.

## Open Questions & Future Work

- [[high-speed-racing-perception-generalization]]

## Archivist Review

I have approved the two primary racing datasets, as they represent foundational benchmarks for the specific niche of high-speed autonomous perception. I also approved the open question regarding high-speed perception generalization because it addresses the identified bottleneck of data scarcity and sim-to-real transfer in dynamic environments. EagleVision itself was rejected as a concept because it functions primarily as a benchmark suite rather than a reusable methodological mechanism.

### Approved Open Questions
- Generalizing High-Speed Racing Perception: This question highlights the critical bottleneck in high-speed perception, where limited real-world data and sim-to-real gaps hinder model generalization.

### Rejected Candidates
- [concept] EagleVision (`eaglevision`) - not_reusable: EagleVision is a specific benchmark dataset/tooling collection rather than a distinct algorithmic concept or architectural component.

## Datasets

- [[indy-autonomous-challenge]]
- [[a2rl-real-competition-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.11400)
- [PDF](https://arxiv.org/pdf/2604.11400)

