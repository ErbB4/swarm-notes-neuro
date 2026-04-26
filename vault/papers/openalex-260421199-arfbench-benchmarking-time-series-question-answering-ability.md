---
# CSL-compatible fields
title: "ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response"
author:
  - literal: "Stephan Xie"
  - literal: "Ben Cohen"
  - literal: "Mononito Goswami"
  - literal: "Jun-Hong Shen"
  - literal: "Emaad Khwaja"
  - literal: "Chenghao Liu"
  - literal: "David Asker"
  - literal: "Othmane Abou-Amal"
  - literal: "Ameet Talwalkar"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21199"

# Custom fields
paper_id: "2604.21199"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  - "arfbench"
concept_slugs:
  - "time-series-question-answering-tsqa"
dataset_slugs:
  - "arfbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:51:58Z"
created_at: "2026-04-26T05:51:58Z"
---

# ARFBench: Benchmarking Time Series Question Answering Ability for Software Incident Response

**Authors**: Stephan Xie, Ben Cohen, Mononito Goswami, Jun-Hong Shen, Emaad Khwaja, Chenghao Liu, David Asker, Othmane Abou-Amal, Ameet Talwalkar
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21199](https://arxiv.org/abs/2604.21199)

## Summary

ARFBench is a new benchmark designed to evaluate the capability of multimodal foundation models to perform Time Series Question Answering (TSQA) in the context of software incident response. Using 750 questions derived from real-world telemetry data, the authors demonstrate that frontier VLMs provide significant improvements over existing baselines. Furthermore, the paper introduces a specialized TSFM-VLM hybrid model and demonstrates that a model-expert oracle significantly surpasses individual performances, suggesting a roadmap for future human-in-the-loop diagnostic systems.

## Key Contributions

- Introduced ARFBench, a new benchmark for Time Series Question Answering (TSQA) comprising 750 questions over 142 real-world production incident time series.
- Conducted an extensive evaluation of LLMs, VLMs, and time series FMs, finding that frontier VLMs outperform current baselines on incident-based anomaly reasoning.
- Developed a TSFM + VLM hybrid approach that achieves performance parity with frontier proprietary models through targeted post-training.
- Proposed a model-expert oracle framework achieving 82.8% F1 and 87.2% accuracy, demonstrating the complementary nature of human experts and current FMs.

## Key Concepts

- [[time-series-question-answering-tsqa]]: A capability of foundation models to answer natural language questions about time series data properties and anomalies.

## Archivist Review

I have approved Time Series Question Answering (TSQA) as it formally defines a new interaction paradigm between natural language and temporal data that extends beyond traditional forecasting. I also approved ARFBench as it provides a specific, high-quality benchmark for this emergent task. Other candidates were rejected to maintain the selective nature of the vault.

### Approved Concepts
- Time Series Question Answering (TSQA): TSQA represents a transition from purely predictive time series modeling to semantic reasoning, defining a new frontier for multimodal foundation models.

## Datasets

- [[arfbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21199)
- [PDF](https://arxiv.org/pdf/2604.21199)

