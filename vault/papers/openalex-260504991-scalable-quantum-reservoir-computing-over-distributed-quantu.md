---
# CSL-compatible fields
title: "Scalable Quantum Reservoir Computing over Distributed Quantum Architectures"
author:
  - literal: "Ioannis Liliopoulos"
  - literal: "Georgios D. Varsamis"
  - literal: "Konstantinos Rallis"
  - literal: "Evangelos Tsipas"
  - literal: "Ioannis G. Karafyllidis"
  - literal: "Georgios Ch. Sirakoulis"
  - literal: "Panagiotis Dimitrakis"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04991"

# Custom fields
paper_id: "2605.04991"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "quantum-machine-learning"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "distributed-quantum-reservoir-computing"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:57:40Z"
created_at: "2026-05-09T05:57:40Z"
---

# Scalable Quantum Reservoir Computing over Distributed Quantum Architectures

**Authors**: Ioannis Liliopoulos, Georgios D. Varsamis, Konstantinos Rallis, Evangelos Tsipas, Ioannis G. Karafyllidis, Georgios Ch. Sirakoulis, Panagiotis Dimitrakis
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04991](https://arxiv.org/abs/2605.04991)

## Summary

This paper explores the scalability of quantum reservoir computing (QRC) for time-series forecasting by benchmarking four architectures incorporating single and distributed reservoirs. By employing both hybrid and fully quantum variants, the study demonstrates that QRC architectures can significantly outperform classical baselines in forecasting accuracy. The results validate that distributed quantum resources can effectively scale QRC performance even under noisy, hardware-informed simulation conditions, offering a modular path for NISQ-era deployment.

## Key Contributions

- Introduces four modular quantum reservoir computing architectures utilizing combinations of single/distributed reservoirs and readout layers.
- Demonstrates quantum-enhanced forecasting accuracy improvements of up to 78.8% in MAE and 72.3% in RMSE compared to classical counterparts.
- Validates the scalability of distributed quantum architectures in hardware-agnostic, noisy NISQ-era simulation environments.

## Open Questions & Future Work

- [[scalability-and-noise-in-distributed-qrc]]

## Key Concepts

- [[distributed-quantum-reservoir-computing]]: A modular approach to reservoir computing that scales by distributing quantum computational resources across multiple reservoirs and readout layers.

## Archivist Review

I have approved the core concept of distributed quantum reservoir computing and the associated open question regarding its scaling behavior and noise sensitivity in the NISQ era. These represent the fundamental architectural contribution of the paper and a specific, well-defined research bottleneck suitable for the vault. No datasets were approved as the paper utilizes generic forecasting evaluation rather than unique, named benchmark datasets.

### Approved Concepts
- Distributed Quantum Reservoir Computing: Central mechanism for scaling quantum reservoir computing to larger problem spaces using multiple hardware units.

### Approved Open Questions
- Scalability of Distributed QRC: Understanding the scaling limits and noise behavior of distributed quantum systems is critical for practical NISQ-era application development. Determining how hardware-agnostic partitioning influences noise accumulation informs the design of robust, modular quantum machine learning pipelines.

## Links

- [Abstract](https://arxiv.org/abs/2605.04991)
- [PDF](https://arxiv.org/pdf/2605.04991)

