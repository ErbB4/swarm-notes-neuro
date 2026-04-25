---
created_at: '2026-04-25T05:38:41Z'
source_papers:
- '[[openalex-260420105-energaizer-fast-and-accurate-gpu-power-estimation-framework]]'
title: Concurrent Kernel and Communication Modeling
---

**Background:** AI workloads increasingly involve kernels that execute concurrently, such as those involving inter-GPU communication, which current analytical performance and power modeling frameworks do not explicitly support.

**Question / Future Work:** There is a need to extend existing analytical performance and power estimation frameworks to model concurrent kernel execution and inter-GPU communication. Current models primarily treat kernels sequentially and rely on the isolation of execution patterns, which makes them unable to accurately estimate resources and power for distributed AI workloads where communication and computation overlap.

**Why It Matters:** Modeling multi-GPU workloads and communication is essential for scaling power estimation to modern, large-scale distributed AI training and inference systems, which are the current industry standard.