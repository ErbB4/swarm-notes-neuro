---
# CSL-compatible fields
title: "PixelFlowCast: Latent-Free Precipitation Nowcasting via Pixel Mean Flows"
author:
  - literal: "Yufeng Zhu"
  - literal: "Chunlei Shi"
  - literal: "Yongchao Feng"
  - literal: "Dan Niu"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10046"

# Custom fields
paper_id: "2605.10046"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "probabilistic-forecasting"
  - "spatiotemporal-modeling"
  - "flow-matching"
  - "diffusion-models"
  - "precipitation-nowcasting"
architectures:
  []
datasets:
  - "sevir"
concept_slugs:
  - "pixel-mean-flows-pmf"
dataset_slugs:
  - "sevir"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:10:20Z"
created_at: "2026-05-14T06:10:20Z"
---

# PixelFlowCast: Latent-Free Precipitation Nowcasting via Pixel Mean Flows

**Authors**: Yufeng Zhu, Chunlei Shi, Yongchao Feng, Dan Niu
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10046](https://arxiv.org/abs/2605.10046)

## Summary

PixelFlowCast is a latent-free, two-stage probabilistic precipitation nowcasting framework designed to overcome the efficiency limitations of diffusion models and the fidelity loss of latent-space models. By employing a deterministic model for global trends and a KANCondNet for spatiotemporal conditioning, it uses a Pixel Mean Flows (PMF) predictor to generate high-quality forecasts in few-step inference. The approach demonstrates superior performance on the SEVIR benchmark, balancing structural fidelity with real-world operational speed requirements.

## Key Contributions

- Introduced PixelFlowCast, a two-stage latent-free framework for high-efficiency, high-fidelity precipitation nowcasting.
- Developed Pixel Mean Flows (PMF) to eliminate latent compression, preserving high-frequency details.
- Outperformed state-of-the-art methods on the SEVIR dataset in terms of both prediction accuracy and inference speed.

## Open Questions & Future Work

- [[physics-informed-latent-free-nowcasting]]

## Key Concepts

- [[pixel-mean-flows-pmf]]: A latent-free, few-step flow-matching predictor for precipitation nowcasting that directly operates in pixel space.

## Archivist Review

I approved the Pixel Mean Flows (PMF) concept because it provides a distinct, high-fidelity alternative to latent-space generative modeling. I rejected the KANCondNet as it functions as a subcomponent, whereas the general KAN architecture is already a concept in the vault. I also included the SEVIR dataset and a pertinent open question regarding physical consistency in latent-free generative models.

### Approved Concepts
- Pixel Mean Flows (PMF): Core innovation replacing latent-space compression with a direct pixel-space flow matching approach for high-fidelity precipitation nowcasting.

### Approved Open Questions
- Physics-Informed Latent-Free Precipitation Nowcasting: Integrating physical consistency into purely data-driven generative models is essential for improving the reliability of extreme weather nowcasting and ensuring that predictions adhere to the underlying governing dynamics of atmospheric systems.

### Rejected Candidates
- [concept] KANCondNet (`kancondnet`) - subcomponent_of_broader_mechanism: This is a specific architectural module (a KAN-based encoder) rather than a broadly reusable mechanism; KANs themselves are already in the vault.

## Datasets

- [[sevir]]

## Links

- [Abstract](https://arxiv.org/abs/2605.10046)
- [PDF](https://arxiv.org/pdf/2605.10046)

