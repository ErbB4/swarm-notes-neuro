---
# CSL-compatible fields
title: "V4FinBench: Benchmarking Tabular Foundation Models, LLMs, and Standard Methods on Corporate Bankruptcy Prediction"
author:
  - literal: "Marcin Kostrzewa"
  - literal: "Sebastian Tomczak"
  - literal: "R. H. Furman"
  - literal: "Anna Poberezhna"
  - literal: "Michał Furgała"
  - literal: "Oleksii Furman"
  - literal: "Maciej Zięba"
issued:
  date-parts:
    - [2026, 5, 11]
url: "https://arxiv.org/abs/2605.10896"

# Custom fields
paper_id: "2605.10896"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "v4finbench"
concept_slugs:
  - "v4finbench"
dataset_slugs:
  - "v4finbench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T06:11:07Z"
created_at: "2026-05-14T06:11:07Z"
---

# V4FinBench: Benchmarking Tabular Foundation Models, LLMs, and Standard Methods on Corporate Bankruptcy Prediction

**Authors**: Marcin Kostrzewa, Sebastian Tomczak, R. H. Furman, Anna Poberezhna, Michał Furgała, Oleksii Furman, Maciej Zięba
**Date**: 2026-05-11
**Paper ID**: [openalex:2605.10896](https://arxiv.org/abs/2605.10896)

## Summary

This paper introduces V4FinBench, a large-scale, open-source benchmark designed to address the scarcity of high-volume, publicly accessible datasets for corporate bankruptcy prediction. The authors evaluate a range of approaches, from standard gradient boosting to advanced TabPFN and QLoRA-finetuned Llama-3-8B models, across multiple forecast horizons and extreme class imbalance. Their results indicate that while TabPFN effectively captures transferable financial distress patterns, LLMs currently struggle to compete with specialized tabular methods in this domain, particularly for long-term forecasting.

## Key Contributions

- Introduces V4FinBench, a large-scale (1M+ records) corporate bankruptcy dataset covering 131 features across 15 years of Visegràd Group economic data.
- Demonstrates that imbalance-aware finetuning of TabPFN achieves performance competitive with or superior to gradient boosting at long-term horizons for high-stakes bankruptcy prediction.
- Finds that QLoRA-finetuned Llama-3-8B significantly underperforms compared to tabular-specialized models (gradient boosting and TabPFN) in bankruptcy forecasting, particularly as the prediction horizon increases.

## Open Questions & Future Work

- [[geographic-transferability-bankruptcy-models]]

## Key Concepts

- [[v4finbench]]: A large-scale corporate bankruptcy benchmark containing over one million company-year records from Visegràd Group economies with 131 features and six prediction horizons.

## Archivist Review

I approved V4FinBench as a significant, large-scale open-source benchmark for corporate bankruptcy prediction, which serves as both a concept (as a framework for evaluation) and a dataset. The open question regarding geographic robustness is a substantial research bottleneck in financial machine learning, addressing the limitation of regionalized model training in global economic contexts. No other candidates were proposed.

### Approved Concepts
- V4FinBench: It provides a significantly larger-scale open-source dataset than existing benchmarks for corporate bankruptcy prediction, filling a gap in high-volume public financial data.

### Approved Open Questions
- Geographic robustness of bankruptcy models: This question is essential for building robust, generalizable financial distress models that are not tethered to the economic specifics of a single geographic region.

## Datasets

- [[v4finbench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.10896)
- [PDF](https://arxiv.org/pdf/2605.10896)

