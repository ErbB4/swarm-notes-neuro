---
created_at: '2026-05-01T06:04:36Z'
source_papers:
- '[[openalex-260425559-representing-the-surface-ocean-in-ecmwfs-data-driven-forecas]]'
title: ML-model trend representation bottleneck
---

**Background:** Data-driven Earth system models currently struggle with systematic biases in prognostic fields that exhibit persistent, long-term trends, such as global mean sea-level rise.

**Question / Future Work:** It remains an unresolved challenge to effectively train machine-learning models to represent oceanic variables that contain strong, non-stationary climate signals, such as absolute sea surface height. Investigating whether training on detrended anomalies or employing alternative normalization strategies can mitigate the tendency of such models to collapse toward a mean historical climatological state is a key area for future development.

**Why It Matters:** Addressing this is critical for the long-term reliability of data-driven Earth system models, as failure to represent trends correctly limits their utility for climate change studies and long-term projection.