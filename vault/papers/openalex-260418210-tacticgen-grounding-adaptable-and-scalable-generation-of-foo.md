---
# CSL-compatible fields
title: "TacticGen: Grounding Adaptable and Scalable Generation of Football Tactics"
author:
  - literal: "Sheng Xu"
  - literal: "Guiliang Liu"
  - literal: "Tarak Kharrat"
  - literal: "Yudong Luo"
  - literal: "Mohamed Aloulou"
  - literal: "Javier López Peña"
  - literal: "Konstantin Sofeikov"
  - literal: "Adam Reid"
  - literal: "Paul Roberts"
  - literal: "Steven Spencer"
  - literal: "Joe Carnall"
  - literal: "Ian McHale"
  - literal: "Oliver Schulte"
  - literal: "Hongyuan Zha"
  - literal: "Wei‐Shi Zheng"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18210"

# Custom fields
paper_id: "2604.18210"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "classifier-guided-tactical-generation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:49:14Z"
created_at: "2026-04-23T05:49:14Z"
---

# TacticGen: Grounding Adaptable and Scalable Generation of Football Tactics

**Authors**: Sheng Xu, Guiliang Liu, Tarak Kharrat, Yudong Luo, Mohamed Aloulou, Javier López Peña, Konstantin Sofeikov, Adam Reid, Paul Roberts, Steven Spencer, Joe Carnall, Ian McHale, Oliver Schulte, Hongyuan Zha, Wei‐Shi Zheng
**Date**: 2026-04-20
**Paper ID**: [openalex:2604.18210](https://arxiv.org/abs/2604.18210)

## Summary

TacticGen is a generative model for football tactics that formulates movement sequences as a multi-agent diffusion transformer problem. By utilizing agent-wise self-attention and context-aware cross-attention, the model captures complex cooperative and competitive dynamics from large-scale tracking data. A key innovation is the classifier guidance mechanism, which allows for steerable tactic generation conditioned on specific strategic objectives at inference time.

## Key Contributions

- Introduces TacticGen, a multi-agent diffusion transformer architecture designed for conditioned tactical generation in association football.
- Implements a classifier-guided generation mechanism enabling tactical adaptation to inference-time objectives specified via rules, language, or neural models.
- Achieves state-of-the-art trajectory prediction performance while demonstrating high strategic realism and utility through expert case studies.

## Open Questions & Future Work

- [[long-horizon-tactical-coherence]]

## Key Concepts

- [[classifier-guided-tactical-generation]]: A framework that uses classifier guidance to steer multi-agent movement generation toward specific tactical objectives at inference time.

## Archivist Review

I have approved the core mechanism, Classifier-Guided Tactical Generation, as it effectively captures a reusable paradigm for steering multi-agent diffusion models. I also approved the open question regarding long-horizon coherence, as it addresses a fundamental bottleneck in applying generative models to complex, structured multi-agent coordination. Other candidates were rejected because they were either subcomponents of the primary mechanism or lacked sufficient generalizability beyond this specific application.

### Approved Concepts
- Classifier-Guided Tactical Generation: This represents a powerful paradigm for steering generative models in multi-agent environments using heterogeneous constraints like natural language or rules.

### Approved Open Questions
- Long-horizon Tactical Coherence: Long-horizon tactical consistency is the primary bottleneck for transitioning from realistic trajectory prediction to useful decision-support tools for professional tactical planning.

## Links

- [Abstract](https://arxiv.org/abs/2604.18210)
- [PDF](https://arxiv.org/pdf/2604.18210)

