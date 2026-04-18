---
created_at: '2026-04-18T05:35:25Z'
source_papers:
- '[[openalex-260413478-deepbullwhip-an-open-source-simulation-and-benchmarking-for]]'
title: Synthetic vs. Real Demand Gap
---

**Background:** Supply chain research frequently relies on synthetic demand models, which may fail to capture the complex, non-stationary dynamics and structural behaviors of real-world supply chains.

**Question / Future Work:** There is a documented, significant disparity between bullwhip metrics derived from synthetic autoregressive demand models and those observed in real-world supply chain data, such as semiconductor billings. It remains an unresolved challenge to develop synthetic demand generators that accurately replicate the regime-switching and heavy-tailed behaviors of empirical data to ensure simulation validity.

**Why It Matters:** The systematic gap between synthetic and real-world demand behavior directly affects the reliability of inventory policy optimization, as synthetic models may drastically underestimate operational risk.

**Evidence:** Benchmark experiments reveal a 155x disparity between synthetic AR(1) and real WSTS bullwhip severity under the Order-Up-To policy.