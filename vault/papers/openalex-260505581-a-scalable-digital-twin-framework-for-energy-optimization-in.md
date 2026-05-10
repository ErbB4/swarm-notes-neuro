---
# CSL-compatible fields
title: "A Scalable Digital Twin Framework for Energy Optimization in Data Centers"
author:
  - literal: "Raphael Hendrigo de Souza Gonçalves"
  - literal: "Wendel Marcos dos Santos"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05581"

# Custom fields
paper_id: "2605.05581"
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
processed_at: "2026-05-10T06:05:14Z"
created_at: "2026-05-10T06:05:14Z"
---

# A Scalable Digital Twin Framework for Energy Optimization in Data Centers

**Authors**: Raphael Hendrigo de Souza Gonçalves, Wendel Marcos dos Santos
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.05581](https://arxiv.org/abs/2605.05581)

## Summary

This paper presents a scalable Digital Twin framework designed to optimize energy efficiency in data centers by integrating IoT sensor data with machine learning-based forecasting. The authors utilize Long Short-Term Memory (LSTM) models to predict energy demand, enabling proactive operational decision-making. Experimental results in a controlled, small-scale environment confirm that the framework reduces power consumption and improves overall Power Usage Effectiveness (PUE). The approach offers a cost-effective path toward more sustainable data center management through intelligent energy monitoring and optimization.

## Key Contributions

- Proposes a scalable Digital Twin framework integrating IoT data acquisition and LSTM-based forecasting for data center energy management.
- Demonstrates improved Power Usage Effectiveness (PUE) and reduced power consumption in a controlled small-scale data center environment.
- Validates the framework's effectiveness in real-time monitoring and operational decision-making using LSTM models for energy demand prediction.

## Open Questions & Future Work

- [[scaling-digital-twins-for-production-data-centers]]

## Archivist Review

The paper describes a standard application of LSTM for energy forecasting within a digital twin context, which does not introduce a novel algorithmic contribution or unique temporal representation suitable for a permanent vault note. I approved a refined version of the open question regarding the scalability gap, as this represents a recurring challenge for time-series-based digital twins in industrial infrastructure.

### Approved Open Questions
- Scaling Digital Twins for Data Centers: The transition from small-scale experimental success to robust performance in large-scale infrastructure remains a critical barrier to the industrial adoption of digital twin technologies for energy optimization.

### Rejected Candidates
- [open_question] Scaling Digital Twins for Data Centers (`scaling-digital-twins-for-large-data-centers`) - duplicate_existing: Renamed to be more precise regarding production environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.05581)
- [PDF](https://arxiv.org/pdf/2605.05581)

