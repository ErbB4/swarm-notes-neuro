---
created_at: '2026-04-30T06:04:41Z'
source_papers:
- '[[openalex-260424326-x-negobox-an-explainable-privacy-budget-negotiation-framewor]]'
title: Negotiation-Aware Threshold Secret Sharing
---

**Background:** Threshold Secret Sharing (TSS) is used to distribute execution authorization for privacy-preserving computations, requiring a threshold of nodes to cooperate to reconstruct a secret key.

**Question / Future Work:** Current privacy-negotiation frameworks typically treat policy enforcement and secure computation/reconstruction as distinct layers. There is an open need to develop a negotiation-aware TSS mechanism that embeds fine-grained policy and budget constraints directly into the secret reconstruction process to ensure atomicity between negotiation and execution.

**Why It Matters:** This is a fundamental bottleneck in bridging policy-driven privacy negotiation with cryptographic security guarantees in decentralized multi-agent systems.