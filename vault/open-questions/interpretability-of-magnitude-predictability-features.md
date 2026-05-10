---
created_at: '2026-05-10T06:04:49Z'
source_papers:
- '[[openalex-240802129-earthquake-magnitudes-depend-on-seismic-history-as-revealed]]'
title: Interpretability of magnitude predictability features
---

**Background:** The prevailing \"separability assumption\" in earthquake forecasting posits that magnitude distributions are statistically independent of the location and time of seismic events, often leading to the adoption of stationary or quasi-stationary Gutenberg-Richter models.

**Question / Future Work:** While the authors demonstrate that earthquake magnitudes contain extractable information from historical catalogs, the precise physical mechanisms and statistical features driving this magnitude predictability remain to be determined. Future research should prioritize ablation studies to decouple the relative contributions of recent seismic history versus regional seismicity rates in the neural network's decision-making process.

**Why It Matters:** Understanding the causal features behind magnitude predictability is essential for bridging the gap between empirical neural network performance and the physical theory of earthquake rupture.

**Evidence:** Specifically, future work should include ablation studies to determine the relative informativeness of the individual encoders, e.g. recent history versus local seismicity rate, to provide deeper insights into the physical mechanisms the model is leveraging.