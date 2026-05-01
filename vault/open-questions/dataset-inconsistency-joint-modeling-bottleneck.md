---
created_at: '2026-05-01T06:04:36Z'
source_papers:
- '[[openalex-260425559-representing-the-surface-ocean-in-ecmwfs-data-driven-forecas]]'
title: Dataset inconsistency joint-modeling bottleneck
---

**Background:** Jointly training machine-learning models across heterogeneous Earth system datasets often requires reconciling differences in how underlying physical variables are constrained and forced across different reanalysis products.

**Question / Future Work:** Datasets from different components of the Earth system (e.g., atmospheric reanalysis and ocean reanalysis) are often produced using different forcing data and boundary conditions, creating inconsistencies when used as a unified training set. Developing methods to harmonize these datasets or designing architectures that explicitly account for these cross-component inconsistencies is necessary to prevent performance degradation in near-surface atmospheric variables.

**Why It Matters:** This bottleneck prevents the seamless scaling of data-driven Earth system models and directly impacts the forecast accuracy of crucial near-surface interactions.