---
# CSL-compatible fields
title: "Electricity price forecasting across Norway's five bidding zones in the post-crisis era"
author:
  - literal: "My Thi Diem Phan"
  - literal: "Trung Tuyen Truong"
  - literal: "Hoai Phuong Ha"
  - literal: "Dat Thanh Nguyen"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26634"

# Custom fields
paper_id: "2604.26634"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "benchmarking"
  - "energy-market"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:49:34Z"
created_at: "2026-05-02T05:49:34Z"
---

# Electricity price forecasting across Norway's five bidding zones in the post-crisis era

**Authors**: My Thi Diem Phan, Trung Tuyen Truong, Hoai Phuong Ha, Dat Thanh Nguyen
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26634](https://arxiv.org/abs/2604.26634)

## Summary

This paper presents a comprehensive benchmarking of electricity price forecasting models across all five Norwegian bidding zones in the post-2021 energy crisis era. Using a new multimodal dataset from 2019 to 2025, the study evaluates various models, ranging from linear ARX benchmarks to advanced deep learning architectures, through strict causal rolling-origin backtesting. The results reveal that LightGBM consistently outperforms other methods, while feature ablation and conditional regime analysis underscore the importance of external market drivers during periods of high price volatility.

## Key Contributions

- Constructed a comprehensive, multimodal hourly dataset covering all five Norwegian Nord Pool electricity bidding zones from 2019 to 2025.
- Evaluated eight model families across all zones, identifying LightGBM as the top performer and validating ridge ARX as a robust linear baseline.
- Demonstrated via conditional regime analysis that while lagged prices are sufficient for general accuracy, external features like reservoir levels are critical for performance during stressed market regimes.

## Open Questions & Future Work

- [[probabilistic-forecasting-extreme-volatility]]

## Archivist Review

The paper provides a localized benchmark study of electricity price forecasting in Norway. While the dataset is useful for this specific domain, it does not represent a broadly reusable benchmarking artifact for the general time-series community. The proposed open question on probabilistic forecasting under volatility is highly relevant and addresses a significant limitation in existing energy market modeling.

### Approved Open Questions
- Probabilistic electricity price forecasting: Point forecasts fail to capture the risk associated with the extreme volatility observed in modern, integrated energy markets; probabilistic approaches are essential for risk management and operational reliability.

## Links

- [Abstract](https://arxiv.org/abs/2604.26634)
- [PDF](https://arxiv.org/pdf/2604.26634)

