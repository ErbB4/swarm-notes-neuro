---
# CSL-compatible fields
title: "Earth-o1: A Grid-free Observation-native Atmospheric World Model"
author:
  - literal: "Junchao Gong"
  - literal: "Kaiyi Xu"
  - literal: "Wangxu Wei"
  - literal: "Siwei Tu"
  - literal: "Jingyi Xu"
  - literal: "Zili Liu"
  - literal: "Zili Liu"
  - literal: "Hang Fan"
  - literal: "Zhiwang Zhou"
  - literal: "Tao Han"
  - literal: "Yi Xiao"
  - literal: "Xinyu Gu"
  - literal: "Zhangrui Li"
  - literal: "Wenlong Zhang"
  - literal: "Hao Chen"
  - literal: "Xiaokang Yang"
  - literal: "Yaqiang Wang"
  - literal: "Lijing Cheng"
  - literal: "Pierre Gentine"
  - literal: "Wanli Ouyang"
  - literal: "Feng Zhang"
  - literal: "Zhe-Min Tan"
  - literal: "Bowen Zhou"
  - literal: "Fenghua Ling"
  - literal: "Ben Fei"
  - literal: "Lei Bai"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06337"

# Custom fields
paper_id: "2605.06337"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "observation-native-atmospheric-world-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:58Z"
created_at: "2026-05-10T06:04:58Z"
---

# Earth-o1: A Grid-free Observation-native Atmospheric World Model

**Authors**: Junchao Gong, Kaiyi Xu, Wangxu Wei, Siwei Tu, Jingyi Xu, Zili Liu, Zili Liu, Hang Fan, Zhiwang Zhou, Tao Han, Yi Xiao, Xinyu Gu, Zhangrui Li, Wenlong Zhang, Hao Chen, Xiaokang Yang, Yaqiang Wang, Lijing Cheng, Pierre Gentine, Wanli Ouyang, Feng Zhang, Zhe-Min Tan, Bowen Zhou, Fenghua Ling, Ben Fei, Lei Bai
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06337](https://arxiv.org/abs/2605.06337)

## Summary

Earth-o1 is a grid-free atmospheric world model designed to bypass the computational and structural limitations of traditional, grid-dependent numerical weather prediction. By learning continuous, 3D physical evolution directly from heterogeneous, ungridded observations, the model enables real-time forecasting and cross-sensor inference without explicit numerical solvers. Evaluation results show that this observation-native approach achieves forecasting performance on par with the operational Integrated Forecasting System (IFS). This work provides a new, scalable paradigm for developing high-fidelity Earth system digital twins.

## Key Contributions

- Introduces Earth-o1, a grid-free atmospheric world model that avoids traditional grid interpolation and explicit numerical solvers.
- Demonstrates direct, real-time forecasting and cross-sensor inference by learning continuous, 3D physical evolution from heterogeneous, ungridded data.
- Achieves surface forecast skill in hindcast evaluations comparable to the operational Integrated Forecasting System (IFS).

## Open Questions & Future Work

- [[uncertainty-quantification-atmospheric-world-models]]
- [[multimodal-sensor-integration-geophysics]]

## Key Concepts

- [[observation-native-atmospheric-world-model]]: A paradigm for modeling atmospheric dynamics by learning continuous 3D physical evolution directly from ungridded observational data, bypassing grid interpolation.

## Archivist Review

I approved the concept of 'Observation-native Atmospheric World Model' as it captures a novel, cross-domain paradigm in geophysical simulation that replaces traditional grid-based methods. The two open questions address critical technical bottlenecks (uncertainty quantification and multimodal scalability) inherent in this new class of models. I rejected no candidates as the submission was already highly selective.

### Approved Concepts
- Observation-native Atmospheric World Model: This represents a fundamental paradigm shift from grid-based numerical weather prediction to continuous, observation-driven simulation.

### Approved Open Questions
- Uncertainty in Atmospheric World Models: Quantifying uncertainty is critical for high-stakes atmospheric forecasting and decision-making, particularly in extreme weather events where model confidence can vary significantly across space and time.
- Multimodal Sensor Integration Generalization: A more diverse data integration enables the model to capture a wider range of physical phenomena and cross-sphere interactions, which is essential for a true digital twin of the Earth system.

## Links

- [Abstract](https://arxiv.org/abs/2605.06337)
- [PDF](https://arxiv.org/pdf/2605.06337)

