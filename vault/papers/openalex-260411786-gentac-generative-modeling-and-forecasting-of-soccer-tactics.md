---
# CSL-compatible fields
title: "GenTac: Generative Modeling and Forecasting of Soccer Tactics"
author:
  - literal: "Jiayuan Rao"
  - literal: "Tianlin Gui"
  - literal: "Haoning Wu"
  - literal: "Yanfeng Wang"
  - literal: "Weidi Xie"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11786"

# Custom fields
paper_id: "2604.11786"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "generative-modeling"
  - "multi-agent-systems"
  - "trajectory-forecasting"
  - "diffusion-models"
architectures:
  []
datasets:
  - "TacBench"
concept_slugs:
  - "gentac"
dataset_slugs:
  - "tacbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:46:34Z"
created_at: "2026-04-16T05:46:34Z"
---

# GenTac: Generative Modeling and Forecasting of Soccer Tactics

**Authors**: Jiayuan Rao, Tianlin Gui, Haoning Wu, Yanfeng Wang, Weidi Xie
**Date**: 2026-04-13
**Paper ID**: [openalex:2604.11786](https://arxiv.org/abs/2604.11786)

## Summary

GenTac is a diffusion-based generative framework designed to model open-play soccer tactics as a stochastic process involving both continuous multi-agent trajectories and discrete semantic events. By grounding spatial dynamics into a predefined tactical event space, the model captures the inherent variance and branching possibilities of match evolution that deterministic methods overlook. The framework supports contextual conditioning for diverse styles and strategic objectives, with empirical results on the TacBench dataset demonstrating superior trajectory accuracy, stylistic nuance, and controllability for counterfactual analysis. Furthermore, the approach shows robust generalization across different dynamic team sports beyond soccer.

## Key Contributions

- Introduces GenTac, a diffusion-based framework that models soccer tactics as a joint distribution of continuous player trajectories and discrete tactical events.
- Achieves high geometric accuracy and structural team consistency in long-horizon forecasting while accounting for multi-agent stochasticity.
- Establishes TacBench, a new benchmark for evaluating generative soccer tactics, demonstrating capabilities in team-specific style simulation and controllable counterfactual generation.

## Key Concepts

- [[gentac]]: A diffusion-based generative framework that models team-sports dynamics as a joint distribution of continuous multi-agent trajectories and discrete tactical events.

## Archivist Review

I have approved GenTac as a significant contribution to multi-agent generative modeling that bridges trajectory forecasting with tactical event semantic grounding. TacBench is accepted as a foundational benchmark for this specific problem domain. All other candidates were rejected as either implementation-specific or covered by the primary contributions.

### Approved Concepts
- GenTac: It introduces a novel framework for modeling multi-agent sports dynamics by jointly handling continuous trajectories and discrete event spaces.

### Rejected Candidates
- [dataset] TacBench (`tacbench`) - duplicate_existing: While a named dataset, it is primary to the evaluation and its inclusion here is redundant if I just list it in the approved_datasets field.

## Datasets

- [[tacbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.11786)
- [PDF](https://arxiv.org/pdf/2604.11786)

