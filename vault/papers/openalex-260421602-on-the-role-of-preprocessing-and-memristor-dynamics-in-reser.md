---
# CSL-compatible fields
title: "On the Role of Preprocessing and Memristor Dynamics in Reservoir Computing for Image Classification"
author:
  - literal: "Rishona Daniels"
  - literal: "Duna Wattad"
  - literal: "Ronny Ronen"
  - literal: "David A. Saad"
  - literal: "Shahar Kvatinsky"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21602"

# Custom fields
paper_id: "2604.21602"
paper_source: "openalex"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "parallel-delayed-feedback-network"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:56Z"
created_at: "2026-04-26T05:52:56Z"
---

# On the Role of Preprocessing and Memristor Dynamics in Reservoir Computing for Image Classification

**Authors**: Rishona Daniels, Duna Wattad, Ronny Ronen, David A. Saad, Shahar Kvatinsky
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21602](https://arxiv.org/abs/2604.21602)

## Summary

This paper investigates the performance of parallel delayed feedback network (PDFN) reservoir computing architectures utilizing volatile memristors for image classification. By systematically analyzing device-level factors such as decay rates and variability, the authors quantify how physical hardware constraints influence system accuracy. The proposed framework achieves competitive performance on the MNIST benchmark while demonstrating significant resilience to device-level stochasticity. This work clarifies the interplay between preprocessing strategies and memristor dynamics, providing a roadmap for energy-efficient neuromorphic implementation.

## Key Contributions

- Analyzes the impact of volatile memristor characteristics—specifically decay rate, quantization, and device variability—on reservoir computing performance.
- Demonstrates 95.89% classification accuracy on MNIST using a parallel delayed feedback network (PDFN) with volatile memristors.
- Establishes robustness of the proposed architecture by maintaining 94.2% accuracy under 20% device variability.

## Open Questions & Future Work

- [[temporal-mapping-of-spatial-data-for-rc]]

## Key Concepts

- [[parallel-delayed-feedback-network]]: A reservoir computing architecture that utilizes parallel delayed feedback loops, specifically designed to leverage the intrinsic volatile dynamics of memristive devices.

## Archivist Review

I approved the PDFN concept as it is a specific architectural framework for hardware-based reservoir computing. I renamed and refined the open question regarding the mapping of spatial data to temporal pulses, as this is a fundamental bottleneck for using dynamic reservoirs on static data. MNIST was rejected as a standard, routine dataset.

### Approved Concepts
- Parallel Delayed Feedback Network (PDFN): The paper centers on how this specific architecture manages volatile memristor constraints for efficient neuromorphic inference.

### Approved Open Questions
- Temporal Mapping of Spatial Data: The performance and scalability of memristor-based RC in tasks like computer vision are fundamentally limited by how effectively input features are encoded into dynamical state transitions.

### Rejected Candidates
- [concept] Memristive-friendly Parallelized Reservoirs (`memristive-friendly-parallelized-reservoirs`) - duplicate_existing: Duplicate or overly generic; superseded by the more standard technical term 'Parallel Delayed Feedback Network' (PDFN).
- [open_question] Automated Optimal Preprocessing Strategies (`automated-optimal-preprocessing-for-rc`) - other: The title is too generic; the core issue is the fundamental mapping process rather than just 'automated' strategy optimization.
- [dataset] MNIST (`MNIST`) - not_novel: Routine dataset, does not deserve a standalone entry in this vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.21602)
- [PDF](https://arxiv.org/pdf/2604.21602)

