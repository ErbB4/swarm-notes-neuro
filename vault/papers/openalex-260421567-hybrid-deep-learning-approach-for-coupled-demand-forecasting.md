---
# CSL-compatible fields
title: "Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization"
author:
  - literal: "Nusrat Yasmin Nadia"
  - literal: "Md Habibul Arif"
  - literal: "Habibor Rahman Rabby"
  - literal: "Md Iftekhar Monzur Tanvir"
  - literal: "Md. Jakir Hossen"
  - literal: "M. F. Mridha"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21567"

# Custom fields
paper_id: "2604.21567"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "optimization"
  - "supply-chain"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:52:12Z"
created_at: "2026-04-26T05:52:12Z"
---

# Hybrid Deep Learning Approach for Coupled Demand Forecasting and Supply Chain Optimization

**Authors**: Nusrat Yasmin Nadia, Md Habibul Arif, Habibor Rahman Rabby, Md Iftekhar Monzur Tanvir, Md. Jakir Hossen, M. F. Mridha
**Date**: 2026-04-23
**Paper ID**: [openalex:2604.21567](https://arxiv.org/abs/2604.21567)

## Summary

This paper proposes a Hybrid AI Framework for Demand-Supply Forecasting and Optimization (HAF-DS), which bridges the gap between predictive demand modeling and prescriptive supply chain decision-making. By integrating an LSTM-based forecasting module directly with a mixed integer linear programming (MILP) layer, the model simultaneously minimizes forecasting error and operational costs. Experimental results on textile and PPE supply chain datasets demonstrate that this coupled approach significantly outperforms traditional isolated methods in both predictive accuracy and key supply chain performance metrics.

## Key Contributions

- Introduces HAF-DS, a hybrid framework that couples LSTM-based demand forecasting with an integrated MILP-based supply chain optimization layer.
- Achieves a 14.7% reduction in MAE and 12.4% reduction in RMSE compared to existing baseline forecasting models on textile and PPE industry data.
- Demonstrates direct operational improvements including a 27.5% reduction in stockouts and a 2.3% increase in service levels via the joint optimization approach.

## Open Questions & Future Work

- [[robustness-to-demand-shocks]]

## Archivist Review

I reviewed the proposed hybrid framework and the open question regarding demand shock robustness. The framework itself is a specific application of established components (LSTM and MILP) and does not qualify as a reusable, general concept. The open question, however, highlights a significant, recurring bottleneck in predictive-prescriptive supply chain systems—managing extreme volatility and constraint violations—which deserves tracking in the vault.

### Approved Open Questions
- Robustness to Demand Shocks: Improving resilience against extreme demand volatility is a fundamental barrier to the deployment of integrated predictive-prescriptive systems in real-world industrial environments.

### Rejected Candidates
- [concept] Hybrid AI Framework for Demand-Supply Forecasting and Optimization (`haf-ds`) - paper_local: The framework is a specific application-level architecture rather than a general, reusable methodological innovation.

## Links

- [Abstract](https://arxiv.org/abs/2604.21567)
- [PDF](https://arxiv.org/pdf/2604.21567)

