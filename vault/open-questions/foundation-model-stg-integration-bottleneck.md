---
created_at: '2026-04-23T05:47:48Z'
source_papers:
- '[[openalex-260105174-fast-efficient-and-effective-long-horizon-forecasting-for-la]]'
title: Foundation Model STG Integration Bottleneck
---

**Background:** Spatial-temporal graph forecasting models traditionally struggle to simultaneously achieve linear computational complexity and long-horizon predictive accuracy due to the quadratic complexity of standard attention and graph convolution mechanisms. While recent approaches have explored techniques like agent tokens and sparse attention to address this scalability bottleneck, these methods often face trade-offs between preserving long-range spatial dependencies and maintaining computational efficiency.

**Question / Future Work:** Future research is needed to determine whether pre-trained foundational temporal representations can be effectively integrated with efficient spatial-temporal graph modeling modules without compromising the linear computational complexity required for large-scale networks.

**Why It Matters:** As STG forecasting moves toward more complex, city-wide applications, foundational models offer a path to improved generalization, yet adapting them to maintain linear-time efficiency remains a challenging bottleneck.