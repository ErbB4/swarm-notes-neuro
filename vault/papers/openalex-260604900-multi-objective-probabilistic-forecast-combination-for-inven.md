---
# CSL-compatible fields
title: "Multi-objective probabilistic forecast combination for inventory demand"
author:
  - literal: "Shengjie Wang"
  - literal: "Yanfei Kang"
  - literal: "Evangelos Spiliotis"
  - literal: "Fotios Petropoulos"
issued:
  date-parts:
    - [2026, 6, 3]
url: "https://arxiv.org/abs/2606.04900"

# Custom fields
paper_id: "2606.04900"
paper_source: "openalex"
domain: "time-series"
tags:
  - "forecasting"
  - "optimization"
  - "decision-making"
architectures:
  []
datasets:
  []
concept_slugs:
  - "multi-objective-probabilistic-forecast-combination"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-06-06T06:13:32Z"
created_at: "2026-06-06T06:13:32Z"
---

# Multi-objective probabilistic forecast combination for inventory demand

**Authors**: Shengjie Wang, Yanfei Kang, Evangelos Spiliotis, Fotios Petropoulos
**Date**: 2026-06-03
**Paper ID**: [openalex:2606.04900](https://arxiv.org/abs/2606.04900)

## Summary

This paper addresses the disconnect between statistical forecast accuracy and operational decision performance in inventory management. The authors introduce a multi-objective probabilistic forecast combination framework that optimizes across both accuracy metrics and inventory-specific costs. By identifying Pareto-optimal combinations, the method allows decision-makers to navigate trade-offs between competing operational targets. Extensive empirical validation on Walmart and Royal Air Force datasets confirms that this integrated approach outperforms traditional single-objective combination techniques.

## Key Contributions

- Proposes a multi-objective optimization framework for combining probabilistic forecasts that balances statistical accuracy with inventory-specific operational objectives.
- Formulates forecast combination as a multi-objective problem to derive Pareto-optimal solutions for complex inventory cost structures.
- Demonstrates superior, more robust inventory decision performance compared to standard single-objective combination methods on real-world retail and spare parts datasets.

## Key Concepts

- [[multi-objective-probabilistic-forecast-combination]]: A framework that optimizes probabilistic forecast combinations against both statistical accuracy and operational decision outcomes via Pareto-optimal trade-offs.

## Archivist Review

I approved the core framework concept as it effectively formalizes the tension between predictive accuracy and operational decision utility, which is a foundational problem in time-series forecasting. The datasets were rejected because they are not provided as public, named benchmarking artifacts that would warrant a persistent, searchable entry in the vault.

### Approved Concepts
- Multi-objective probabilistic forecast combination: It addresses the common misalignment between statistical forecast accuracy and operational decision-making efficiency in high-stakes inventory management.

### Rejected Candidates
- [dataset] Walmart retail data (`walmart-retail-data`) - low_impact: Generic retail dataset description, not a specific, named, and public benchmark artifact.
- [dataset] Royal Air Force spare parts data (`royal-air-force-spare-parts-data`) - low_impact: Proprietary or generic domain-specific data without public distribution or standard benchmark status.

## Links

- [Abstract](https://arxiv.org/abs/2606.04900)
- [PDF](https://arxiv.org/pdf/2606.04900)

