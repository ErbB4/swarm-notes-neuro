---
# CSL-compatible fields
title: "Efficient and Adaptive Human Activity Recognition via LLM Backbones"
author:
  - literal: "Aleksandr Bredikhin"
  - literal: "Philippe Lalanda"
  - literal: "German Vega"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12019"

# Custom fields
paper_id: "2605.12019"
paper_source: "openalex"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "structured-convolutional-projection"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-15T06:16:39Z"
created_at: "2026-05-15T06:16:39Z"
---

# Efficient and Adaptive Human Activity Recognition via LLM Backbones

**Authors**: Aleksandr Bredikhin, Philippe Lalanda, German Vega
**Date**: 2026-05-12
**Paper ID**: [openalex:2605.12019](https://arxiv.org/abs/2605.12019)

## Summary

This paper proposes repurposing pretrained LLMs as robust, adaptive temporal backbones for Human Activity Recognition (HAR) by replacing task-specific architectures. The authors introduce a structured convolutional projection to map inertial sensor data into the LLM latent space, while utilizing Low-Rank Adaptation (LoRA) to keep the backbone frozen. This methodology reduces training costs and data requirements while providing superior performance in cross-dataset and few-shot HAR scenarios. The approach effectively combines the local feature extraction of convolutional frontends with the long-range dependency modeling of LLM foundations.

## Key Contributions

- Introduced a paradigm for leveraging frozen LLMs as generic temporal backbones for sensor-based Human Activity Recognition (HAR).
- Developed a structured convolutional projection that effectively bridges the modality gap between inertial time-series data and language model latent spaces.
- Demonstrated that LoRA-based fine-tuning of frozen LLM backbones achieves competitive accuracy with significantly reduced parameter count and improved data efficiency in few-shot scenarios.

## Key Concepts

- [[structured-convolutional-projection]]: A technique for projecting multivariate inertial sensor data into the latent space of LLMs for downstream activity recognition.

## Archivist Review

The paper proposes a specific modality-bridging technique (structured convolutional projection) that is sufficiently novel and reusable for time-series-to-LLM integration tasks to warrant a vault note. I have rejected no other candidates as none were provided. The review focused on identifying a reusable mechanism for cross-modal embedding that avoids generic architectural labels.

### Approved Concepts
- Structured Convolutional Projection: It provides a novel methodology for bridging the modality gap between heterogeneous inertial time series data and frozen LLM backbones.

## Links

- [Abstract](https://arxiv.org/abs/2605.12019)
- [PDF](https://arxiv.org/pdf/2605.12019)

