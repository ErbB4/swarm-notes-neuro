---
created_at: '2026-05-16T06:03:33Z'
source_papers:
- '[[openalex-260513743-ghgbench-a-unified-multi-entity-multi-task-benchmark-for-car]]'
title: Cross-city emissions generalization bottleneck
---

**Background:** Entity-level greenhouse gas emission prediction is currently challenged by high data fragmentation and significant generalization gaps across geographic regions and sectors. Existing models struggle with cross-city transferability and reliance on static factor lookups.

**Question / Future Work:** Research is required to develop robust architectures—including advanced multimodal fusion and foundation models—that can overcome the failure modes identified in current emission forecasting, particularly the 'catastrophic' degradation observed during cross-city transfer and the limitations of sector-factor lookup methods.

**Why It Matters:** This addresses a key bottleneck for climate-tech scalability where models fail to generalize to new cities or sectors without significant performance loss.

**Evidence:** The benchmark also exposes systematic failure modes (catastrophic city transfer and the sector-factor lookup ceiling) that mark where deep, multimodal, and foundation models must improve next.