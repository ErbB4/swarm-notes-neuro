---
# CSL-compatible fields
title: "RopeDreamer: A Kinematic Recurrent State Space Model for Dynamics of Flexible Deformable Linear Objects"
author:
  - literal: "Tim Missal"
  - literal: "Lucas Domingues"
  - literal: "Berk Guler"
  - literal: "Simon Manschitz"
  - literal: "Jan Peters"
  - literal: "Paula Dornhofer Paro Costa"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.28161"

# Custom fields
paper_id: "2604.28161"
paper_source: "openalex"
domain: "robotics"
tags:
  - "robotics"
  - "dynamics-modeling"
  - "latent-space-models"
architectures:
  []
datasets:
  []
concept_slugs:
  - "quaternionic-kinematic-chain-representation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T06:03:49Z"
created_at: "2026-05-03T06:03:49Z"
---

# RopeDreamer: A Kinematic Recurrent State Space Model for Dynamics of Flexible Deformable Linear Objects

**Authors**: Tim Missal, Lucas Domingues, Berk Guler, Simon Manschitz, Jan Peters, Paula Dornhofer Paro Costa
**Date**: 2026-04-30
**Paper ID**: [openalex:2604.28161](https://arxiv.org/abs/2604.28161)

## Summary

RopeDreamer is a latent dynamics framework for the robotic manipulation of Deformable Linear Objects (DLOs) that addresses the high-dimensional, non-linear dynamics and physical integrity challenges. By utilizing a Quaternionic Kinematic Chain representation instead of Cartesian positions, the model inherently preserves link-length constancy and topological integrity during complex deformations. A novel dual-decoder architecture further improves accuracy by decoupling state reconstruction from trajectory forecasting, yielding significant improvements in both prediction error and inference efficiency over long-horizon tasks.

## Key Contributions

- Proposes RopeDreamer, a latent dynamics model for DLOs using a Quaternionic Kinematic Chain representation to ensure physical link-length constancy.
- Introduces a dual-decoder architecture that decouples state reconstruction from future-state prediction to enforce physical awareness in latent dynamics.
- Achieves a 40.52% reduction in open-loop prediction error over 50-step horizons and 31.17% faster inference compared to current state-of-the-art DLO dynamics models.

## Open Questions & Future Work

- [[hierarchical-latent-reconstruction-bottleneck]]
- [[online-system-identification-sim-to-real]]

## Key Concepts

- [[quaternionic-kinematic-chain-representation]]: A representation for deformable objects that encodes geometry as relative quaternion rotations to maintain topological and physical integrity.

## Archivist Review

The approved concept provides a robust, reusable geometric constraint for modeling flexible linear structures that avoids physical artifacts like link stretching. The approved open questions address two foundational challenges in robotics and dynamics modeling: the information bottleneck in latent reconstruction and the domain shift in deployment, both of which are high-impact research areas. All other candidates were omitted to keep the knowledge vault focused on high-level mechanisms and foundational research problems.

### Approved Concepts
- Quaternionic Kinematic Chain Representation: It solves the physical constraint problem of link stretching in DLO modeling by moving from Cartesian coordinates to a rotation-based manifold.

### Approved Open Questions
- Hierarchical Latent Architecture Development: The paper explicitly identifies an initial reconstruction trade-off caused by the information bottleneck of the latent manifold, which negatively impacts the starting accuracy of their predictions.
- Online System Identification Adaptation: The authors explicitly mention this as a key research avenue for deploying their model on physical hardware, addressing the limitation that their current model is primarily evaluated in simulation.

## Links

- [Abstract](https://arxiv.org/abs/2604.28161)
- [PDF](https://arxiv.org/pdf/2604.28161)

