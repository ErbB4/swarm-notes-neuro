---
created_at: '2026-05-14T06:11:00Z'
source_papers:
- '[[openalex-260510428-a-taxonomy-of-event-linked-perpetual-futures-variant-designs]]'
title: Conditional Probability Denominator Instability
---

**Background:** Conditional-probability perpetuals track the ratio of two related event probabilities, which creates a mathematical singularity when the conditioning event's probability approaches zero.

**Question / Future Work:** There is a need to establish formal design requirements for handling the denominator instability that occurs in conditional-probability perpetuals. Specifically, it remains unresolved whether to implement a strict probability floor, a dynamic trading halt, or another mechanism to maintain contract stability as the conditioning event becomes improbable.

**Why It Matters:** This is a critical failure mode for this specific derivative variant, and without a standardized approach, implementations will be highly unstable during periods of low probability for the conditioning event.

**Evidence:** Any conditional-probability perpetual whose underlying is computed as I_t^{cond} = I_t^{(A \cap B)} / I_t^{(B)} ... inherits an unbounded local sensitivity \partial I^{cond} / \partial I^{(B)} as the conditioning event’s marginal I_t^{(B)} \to 0. Without explicit denominator floors, conditioning-event halt rules, or early termination triggers, the contract’s underlying becomes ill-defined and unhedgeable.