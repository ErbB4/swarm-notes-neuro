---
# CSL-compatible fields
title: "ActionParty: Multi-Subject Action Binding in Generative Video Games"
author:
  - literal: "Alexander Pondaven"
  - literal: "Ziyi Wu"
  - literal: "Igor Gilitschenski"
  - literal: "Philip Torr, Sergey Tulyakov"
  - literal: "Fabio Pizzati"
  - literal: "Aliaksandr Siarohin"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02330"

# Custom fields
paper_id: "2604.02330"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "generative-models"
  - "video-generation"
  - "world-models"
  - "multi-agent-systems"
architectures:
  []
datasets:
  - "Melting Pot"
concept_slugs:
  - "subject-state-tokens"
dataset_slugs:
  - "melting-pot"
skill: "GeneralMLSkill"
processed_at: "2026-04-04T20:07:11Z"
created_at: "2026-04-04T20:07:11Z"
---

# ActionParty: Multi-Subject Action Binding in Generative Video Games

**Authors**: Alexander Pondaven, Ziyi Wu, Igor Gilitschenski, Philip Torr, Sergey Tulyakov, Fabio Pizzati, Aliaksandr Siarohin
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02330](https://arxiv.org/abs/2604.02330)

## Summary

ActionParty is a generative world model designed to overcome the limitations of single-agent video diffusion by enabling multi-subject action binding. It utilizes subject state tokens to maintain persistent representations of individual entities, which are then integrated with video latents through a spatial biasing mechanism. This approach effectively disentangles the rendering of the environment from the specific actions performed by individual agents, allowing for robust autoregressive tracking and high-fidelity control in interactive environments. The model demonstrates unprecedented multi-agent control in the Melting Pot benchmark, significantly outperforming existing baselines in action-following accuracy and identity maintenance.

## Key Contributions

- Introduces ActionParty, a multi-subject world model that achieves simultaneous control of up to seven players.
- Proposes subject state tokens to decouple individual agent actions from global frame rendering.
- Demonstrates improved action-following accuracy and identity consistency on 46 environments within the Melting Pot benchmark.

## Key Concepts

- [[subject-state-tokens]]: Latent variables that persistently represent individual subject states to enable independent control and tracking within a global generative context.

## Archivist Review

I have approved 'Subject State Tokens' as a reusable architectural pattern for entity-centric generative modeling. I rejected the model name 'ActionParty' to avoid storing paper-specific artifacts, preferring to focus on the underlying technique. I also approved the 'Melting Pot' benchmark as it is a widely recognized and reusable testbed for multi-agent interactive environments.

### Approved Concepts
- Subject State Tokens: This mechanism provides a scalable way to disentangle individual entity control from global video generation, addressing a fundamental limitation in current world models.

### Rejected Candidates
- [concept] ActionParty (`actionparty`) - subcomponent_of_broader_mechanism: This is the name of the specific model proposed in the paper, and the core reusable mechanism (subject state tokens) is better captured as a standalone concept.

## Datasets

- [[melting-pot]]

## Links

- [Abstract](https://arxiv.org/abs/2604.02330)
- [PDF](https://arxiv.org/pdf/2604.02330)

