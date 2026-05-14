---
created_at: '2026-05-14T06:11:00Z'
source_papers:
- '[[openalex-260510428-a-taxonomy-of-event-linked-perpetual-futures-variant-designs]]'
title: Event-Basket Rebalancing Conventions
---

**Background:** Event-basket perpetuals are structured as weighted sums of multiple constituent event probabilities, but their terminal behavior and margin requirements differ significantly from single-market contracts.

**Question / Future Work:** There is a lack of consensus on the optimal rebalancing and weight-specification rules for event-basket perpetuals, such as whether weights should be static, equal, or volume-weighted, and whether baskets should use 'drop-on-resolution' or 'no-rebalancing' rules. Defining these rules is essential because different choices lead to distinct terminal payoff distributions and potential index discontinuities.

**Why It Matters:** The absence of standard rebalancing conventions for these instruments makes them difficult to benchmark and creates ambiguity in how traders should hedge and how venues should structure margin.

**Evidence:** Rebalancing rules: ... (1) No rebalancing ... (2) Drop-on-resolution ... (3) Add-on-listing ... The choice is venue-side; specification should commit explicitly.