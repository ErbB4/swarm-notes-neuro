---
# CSL-compatible fields
title: "A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir"
author:
  - literal: "Diego Gutiérrez‐Oribio"
  - literal: "Ioannis Stefanou"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26802"

# Custom fields
paper_id: "2604.26802"
paper_source: "openalex"
domain: "time-series"
tags:
  - "time-series-augmented-generation"
  - "uncertainty-weighted-mean-squared-error"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:50:26Z"
created_at: "2026-05-02T05:50:26Z"
---

# A Control Framework for Induced Seismicity Mitigation in Groningen Gas Reservoir

**Authors**: Diego Gutiérrez‐Oribio, Ioannis Stefanou
**Date**: 2026-04-29
**Paper ID**: [openalex:2604.26802](https://arxiv.org/abs/2604.26802)

## Summary

This paper introduces a control framework for mitigating induced seismicity in the Groningen gas field by balancing extraction rates with seismic risk constraints. By coupling pore-pressure diffusion models with stochastic earthquake event generation, the authors derive a feedback control strategy that optimizes well-rate commands. The approach explicitly manages operational flux limits and provides a systematic way to regulate seismicity levels while satisfying production demands. Numerical experiments validate the model's efficacy across various injection/extraction scenarios.

## Key Contributions

- Proposes a control-oriented methodology for gas reservoir operation to minimize induced seismicity while meeting production targets.
- Integrates a cascade model of pore-pressure diffusion and seismicity rate dynamics with a stochastic event-generation procedure for synthetic earthquake cataloging.
- Develops a robust digital feedback controller that regulates seismicity rates under actuator saturation constraints such as flux limits.

## Open Questions & Future Work

- [[unobservable-seismicity-rate-estimation-bottleneck]]

## Archivist Review

The submission was reviewed against the standard of long-term utility in the TimeSeriesSkill vault. The proposed control framework is highly domain-specific to geophysics and seismicity management, lacking the general-purpose algorithmic structure required for permanent concept inclusion. However, the identified bottleneck regarding the estimation of unobservable latent variables (SR) from sparse, stochastic event data represents a persistent, recurring problem in feedback control for complex temporal systems, and thus merits inclusion as an open question.

### Approved Open Questions
- Unobservable Seismicity Rate Estimation: The inability to measure the control variable (SR) directly constitutes a primary bottleneck in implementing closed-loop seismic risk mitigation in real-world reservoirs. Robust estimation is essential for the reliability of any feedback controller.

## Links

- [Abstract](https://arxiv.org/abs/2604.26802)
- [PDF](https://arxiv.org/pdf/2604.26802)

