---
# CSL-compatible fields
title: "GHGbench: A Unified Multi-Entity, Multi-Task Benchmark for Carbon Emission Prediction"
author:
  - literal: "Yifan Duan"
  - literal: "Siyuan Zheng"
  - literal: "Lihuan Li"
  - literal: "Chao Xue"
  - literal: "Flora D. Salim"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.13743"

# Custom fields
paper_id: "2605.13743"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "benchmark"
architectures:
  []
datasets:
  - "ghgbench"
concept_slugs:
  - "ghgbench"
dataset_slugs:
  - "ghgbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:03:33Z"
created_at: "2026-05-16T06:03:33Z"
---

# GHGbench: A Unified Multi-Entity, Multi-Task Benchmark for Carbon Emission Prediction

**Authors**: Yifan Duan, Siyuan Zheng, Lihuan Li, Chao Xue, Flora D. Salim
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.13743](https://arxiv.org/abs/2605.13743)

## Summary

GHGbench is a unified benchmark platform for carbon emission prediction that addresses data fragmentation by providing harmonized datasets for both company-level and building-level forecasting. It defines rigorous evaluation tasks, including in-distribution and cross-region transfer, while establishing baselines across multiple architectures ranging from gradient-boosted trees to tabular foundation models. The study reveals critical insights into model performance, notably highlighting the effectiveness of multimodal remote-sensing features in challenging generalization scenarios and the persistent difficulty of cross-city emission prediction.

## Key Contributions

- Introduces GHGbench, a comprehensive benchmark featuring 32,000+ company records and 491,591 building records across 26 metropolitan areas.
- Demonstrates that tabular foundation models outperform gradient-boosted trees on cross-city building-emissions forecasting tasks, reaching statistical significance via paired-bootstrap testing.
- Establishes that multimodal remote-sensing embeddings provide measurable performance gains specifically when tabular-only generalization reaches its limits.
- Identifies systemic failure modes in emission prediction, including poor city-to-city transferability and the limitations of sector-factor-based estimation.

## Open Questions & Future Work

- [[cross-city-emissions-generalization-bottleneck]]

## Key Concepts

- [[ghgbench]]: A unified multi-entity, multi-task benchmark for company- and building-level carbon emission prediction.

## Archivist Review

The paper provides a significant contribution by consolidating fragmented carbon-emission data into a unified benchmark. I approved GHGbench as both a concept and a dataset, as it provides a structured platform for climate-related time-series research. I also approved a specific open question focused on the observed failure modes in cross-city generalization, as it identifies a concrete, domain-specific research challenge for future predictive models.

### Approved Concepts
- GHGbench: It establishes a standardized framework for carbon emission prediction across multiple entities and scales, addressing the fragmentation of existing datasets.

### Approved Open Questions
- Cross-city emissions generalization bottleneck: This addresses a key bottleneck for climate-tech scalability where models fail to generalize to new cities or sectors without significant performance loss.

## Datasets

- [[ghgbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.13743)
- [PDF](https://arxiv.org/pdf/2605.13743)

