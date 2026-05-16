---
# CSL-compatible fields
title: "SpikeProphecy: A Large-Scale Benchmark for Autoregressive Neural Population Forecasting"
author:
  - literal: "John R. Minnick"
  - literal: "Jinghui Geng"
  - literal: "Kamran Hussain"
  - literal: "Jesus Gonzalez-Ferrer"
  - literal: "Ash Robbins"
  - literal: "Mohammed A. Mostajo-Radji"
  - literal: "David Haussler"
  - literal: "Jason K. Eshraghian"
  - literal: "Mircea Teodorescu"
issued:
  date-parts:
    - [2026, 5, 13]
url: "https://arxiv.org/abs/2605.12992"

# Custom fields
paper_id: "2605.12992"
paper_source: "openalex"
domain: "nlp"
tags:
  - "time-series-forecasting"
  - "neuroscience"
  - "benchmarking"
architectures:
  []
datasets:
  []
concept_slugs:
  - "population-metric-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T06:01:39Z"
created_at: "2026-05-16T06:01:39Z"
---

# SpikeProphecy: A Large-Scale Benchmark for Autoregressive Neural Population Forecasting

**Authors**: John R. Minnick, Jinghui Geng, Kamran Hussain, Jesus Gonzalez-Ferrer, Ash Robbins, Mohammed A. Mostajo-Radji, David Haussler, Jason K. Eshraghian, Mircea Teodorescu
**Date**: 2026-05-13
**Paper ID**: [openalex:2605.12992](https://arxiv.org/abs/2605.12992)

## Summary

SpikeProphecy is a large-scale benchmark designed to advance autoregressive neural population forecasting beyond aggregate correlation metrics. By introducing a novel population metric decomposition, the authors separate performance into temporal, spatial, and alignment-based dimensions, revealing critical model behavior previously hidden by scalar metrics. Evaluated on over 89,000 neurons across seven architectural families, the benchmark exposes biophysical constraints in spike forecasting and provides a rigorous evaluation protocol for neural population dynamics.

## Key Contributions

- Introduces SpikeProphecy, the first large-scale benchmark for causal, autoregressive neural population spike-count forecasting.
- Proposes a population metric decomposition that isolates temporal fidelity, spatial pattern accuracy, and magnitude-invariant alignment to provide deeper model evaluation.
- Demonstrates consistent brain-region predictability rankings across seven diverse model architectures that persist after controlling for firing statistics.

## Open Questions & Future Work

- [[sub-poisson-forecasting-bottleneck]]

## Key Concepts

- [[population-metric-decomposition]]: A framework for decomposing neural spike count forecasting metrics into temporal, spatial, and magnitude-invariant components.

## Archivist Review

I approved the population metric decomposition as it represents a sophisticated, reusable methodological contribution for evaluating high-dimensional time series. I also approved the sub-Poisson forecasting bottleneck because it highlights a fundamental limitation in current neural forecasting metrics that requires structural research beyond just adding data or architecture depth. I rejected the benchmark datasets as they are established community standards and not standalone contributions that necessitate a new vault entry in this context.

### Approved Concepts
- Population metric decomposition: Provides a rigorous framework for evaluating high-dimensional neural population dynamics by avoiding the information loss inherent in aggregate scalar metrics.

### Approved Open Questions
- Sub-Poisson forecasting bottleneck: Identifying the root of the sub-Poisson noise floor is essential for accurately assessing predictive progress in neural forecasting and avoiding metric-induced bias.

### Rejected Candidates
- [dataset] Steinmetz 2019 / IBL Repeated Site (`steinmetz-2019-ibl-repeated-site`) - low_impact: These datasets are specific to a domain and are often used as standard reference sets; I am prioritizing more novel methodological concepts over specific benchmark datasets per policy.

## Links

- [Abstract](https://arxiv.org/abs/2605.12992)
- [PDF](https://arxiv.org/pdf/2605.12992)

