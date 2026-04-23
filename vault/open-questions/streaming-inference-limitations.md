---
created_at: '2026-04-23T05:49:06Z'
source_papers:
- '[[openalex-260418367-east-early-action-prediction-sampling-strategy-with-token-ma]]'
title: Streaming Inference Challenges
---

**Background:** Video processing models, including those designed for early action prediction, frequently face challenges with high computational costs and the inability to handle streaming, real-time video inputs.

**Question / Future Work:** Current encoder architectures often rely on sliding-window inference rather than true streaming, which limits the potential for low-latency, real-time applications and prevents capturing natural, continuous temporal progression.

**Why It Matters:** Developing streaming-capable architectures is essential for real-world deployment in safety-critical, time-sensitive applications.

**Evidence:** Our encoder does not perform causal inference, which necessitates sliding-window inference over the temporal dimension... it prevents streaming inference, which would better capture natural temporal progression and long-term context.