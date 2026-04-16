---
# CSL-compatible fields
title: "SLALOM: Simulation Lifecycle Analysis via Longitudinal Observation Metrics for Social Simulation"
author:
  - literal: "Juhoon Lee"
  - literal: "Joseph Seering"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11466"

# Custom fields
paper_id: "2604.11466"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "slalom-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:47:18Z"
created_at: "2026-04-16T05:47:18Z"
---

# SLALOM: Simulation Lifecycle Analysis via Longitudinal Observation Metrics for Social Simulation

**Authors**: Juhoon Lee, Joseph Seering
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11466](https://arxiv.org/abs/2604.11466)

## Summary

This paper addresses the validity crisis in LLM-based social simulation by moving from outcome-centric evaluation to process-based validation. The authors introduce SLALOM, a framework that employs Pattern-Oriented Modeling to define intermediate phase-based constraints (SLALOM gates) within social simulations. By applying Dynamic Time Warping to align simulated multivariate trajectories with empirical ground truth, the framework provides a quantitative mechanism to ensure structural realism and sociological plausibility in agent-based modeling.

## Key Contributions

- Introduces SLALOM, a framework for evaluating LLM agent social simulations based on process fidelity rather than final outcome accuracy.
- Utilizes Pattern-Oriented Modeling to define intermediate 'SLALOM gates' as structural constraints for social simulation trajectories.
- Applies Dynamic Time Warping (DTW) to quantify alignment between simulated multivariate time series and empirical social science data.

## Open Questions & Future Work

- [[evaluating-non-linear-social-simulations]]

## Key Concepts

- [[slalom-framework]]: A framework for evaluating social simulations by enforcing process fidelity through intermediate temporal constraints rather than focusing solely on final outcomes.

## Archivist Review

I have approved the SLALOM framework as it establishes a distinct methodology for process-based evaluation of agent-based models. I also approved the open question regarding non-linear social simulations, as it identifies a clear, persistent boundary of current temporal alignment metrics like DTW. Other minor technical components were rejected to maintain the focus on the primary architectural innovation of the paper.

### Approved Concepts
- SLALOM (Simulation Lifecycle Analysis via Longitudinal Observation Metrics): It provides a novel process-centric evaluation paradigm for agent-based social simulations, specifically addressing the validity crisis in LLM-based modeling.

### Approved Open Questions
- Evaluating Non-Linear Social Simulations: This is a critical limitation for the scalability and applicability of process-based validation frameworks to diverse social phenomena where non-linearity is a core feature.

## Links

- [Abstract](https://arxiv.org/abs/2604.11466)
- [PDF](https://arxiv.org/pdf/2604.11466)

