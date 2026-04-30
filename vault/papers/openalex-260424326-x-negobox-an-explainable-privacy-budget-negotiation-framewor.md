---
# CSL-compatible fields
title: "X-NegoBox: An Explainable Privacy-Budget Negotiation Framework for Secure Peer-to-Peer Energy Data Exchange"
author:
  - literal: "Poushali Sengupta"
  - literal: "Sabita Maharjan"
  - literal: "Frank Eliassen"
  - literal: "Yan ZHANG"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24326"

# Custom fields
paper_id: "2604.24326"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "x-negobox-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:04:41Z"
created_at: "2026-04-30T06:04:41Z"
---

# X-NegoBox: An Explainable Privacy-Budget Negotiation Framework for Secure Peer-to-Peer Energy Data Exchange

**Authors**: Poushali Sengupta, Sabita Maharjan, Frank Eliassen, Yan ZHANG
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.24326](https://arxiv.org/abs/2604.24326)

## Summary

X-NegoBox addresses the rigidity of existing privacy-budgeting mechanisms in peer-to-peer energy trading by introducing an autonomous negotiation framework. Using the APBNP protocol, the system dynamically adjusts privacy budgets based on context-aware factors like data sensitivity and requester trust, while providing transparent justifications via an Explainable Agreement Layer. By executing requester code in secure sandboxes and sharing only sanitized results, the framework effectively balances data utility, privacy, and user participation.

## Key Contributions

- Introduced X-NegoBox, an explainable framework for dynamic privacy-budget negotiation in decentralized energy data exchange.
- Developed the APBNP protocol, which leverages trust, feature sensitivity, and risk-aware pricing to automate privacy decision-making.
- Implemented an Explainable Agreement Layer (X-Contract) to provide transparent justifications for privacy-related requests.

## Open Questions & Future Work

- [[negotiation-aware-threshold-secret-sharing]]

## Key Concepts

- [[x-negobox-framework]]: An explainable framework for negotiating adaptive privacy budgets in decentralized data exchange environments.

## Archivist Review

The review focused on the framework's core contribution to decentralized privacy negotiation. I approved the X-NegoBox Framework as a representative mechanism for explainable, adaptive privacy negotiation. The APBNP protocol was rejected as it is a subordinate mechanism within the broader framework. I also approved a research-heavy open question regarding the integration of negotiation into cryptographic protocols, as this addresses a significant gap in policy-aware secure computation.

### Approved Concepts
- X-NegoBox Framework: It introduces a novel framework for dynamic, explainable privacy negotiation in decentralized systems, which is distinct from fixed-policy approaches.

### Approved Open Questions
- Negotiation-Aware Threshold Secret Sharing: This is a fundamental bottleneck in bridging policy-driven privacy negotiation with cryptographic security guarantees in decentralized multi-agent systems.

### Rejected Candidates
- [concept] APBNP (`apbnp`) - subcomponent_of_broader_mechanism: This protocol is a functional subcomponent of the overarching X-NegoBox framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.24326)
- [PDF](https://arxiv.org/pdf/2604.24326)

