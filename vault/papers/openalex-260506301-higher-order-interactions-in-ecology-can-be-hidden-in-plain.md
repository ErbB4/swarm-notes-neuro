---
# CSL-compatible fields
title: "Higher-order interactions in ecology can be hidden in plain sight"
author:
  - literal: "Violeta Calleja-Solanas"
  - literal: "Santiago Lamata-Otín"
  - literal: "Carlos Gómez-Ambrosi"
  - literal: "Jesús Gómez-Gardeñes"
  - literal: "Sandro Meloni"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06301"

# Custom fields
paper_id: "2605.06301"
paper_source: "openalex"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T06:04:41Z"
created_at: "2026-05-10T06:04:41Z"
---

# Higher-order interactions in ecology can be hidden in plain sight

**Authors**: Violeta Calleja-Solanas, Santiago Lamata-Otín, Carlos Gómez-Ambrosi, Jesús Gómez-Gardeñes, Sandro Meloni
**Date**: 2026-05-07
**Paper ID**: [openalex:2605.06301](https://arxiv.org/abs/2605.06301)

## Summary

This paper investigates the limits of inferring higher-order ecological interactions from abundance time series, demonstrating that higher-order Lotka-Volterra dynamics can often be effectively represented by simpler pairwise models. The authors reveal a fundamental mechanism identifiability issue where different interaction structures produce near-indistinguishable dynamics. Consequently, they conclude that time-series data alone is insufficient for identifying complex ecological structures and advocate for the inclusion of additional ecological constraints.

## Key Contributions

- Demonstrates that higher-order Lotka-Volterra dynamics can often be reproduced by effective pairwise models, rendering interaction inference from time-series alone ambiguous.
- Identifies a fundamental mechanism identifiability problem where distinct ecological interaction structures generate nearly identical time-series outputs.
- Argues that reliably inferring ecological interaction structures necessitates integrating external ecological information beyond abundance time series.

## Open Questions & Future Work

- [[ecological-higher-order-interaction-identifiability]]

## Archivist Review

The paper identifies a fundamental identifiability constraint in time-series modeling where complex (higher-order) interactions are effectively masked by simpler (pairwise) models. I have approved the open question regarding the theoretical and practical conditions for overcoming this non-identifiability, as it represents a significant challenge for mechanistic inference in complex dynamical systems. No new concepts were approved as the primary contribution is a negative result regarding model identifiability rather than a novel, reusable algorithmic framework.

### Approved Open Questions
- Identifiability of Ecological HOIs: This issue is critical because it addresses the core problem of model identification in complex systems; relying solely on predictive power from time-series fits can lead to fundamentally incorrect conclusions about species interactions, which has profound implications for conservation, management, and understanding ecological stability.

## Links

- [Abstract](https://arxiv.org/abs/2605.06301)
- [PDF](https://arxiv.org/pdf/2605.06301)

