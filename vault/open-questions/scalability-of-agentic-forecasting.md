---
created_at: '2026-05-17T06:06:57Z'
source_papers:
- '[[openalex-260514389-nexus-an-agentic-framework-for-time-series-forecasting]]'
title: Scalability of Agentic Forecasting
---

**Background:** Time series forecasting has traditionally relied on either numerical foundation models or large language models, the former of which struggle with unstructured contextual data and the latter of which lack intrinsic temporal modeling mechanisms.

**Question / Future Work:** While agentic frameworks show promise in integrating multi-modal context, their scalability to long-horizon, high-frequency, or large-scale datasets remains limited by the significant computational and latency costs associated with multi-stage LLM agent invocations. Developing efficient agentic architectures or distillation methods that preserve reasoning capabilities while reducing inference overhead is a critical barrier for production deployment.

**Why It Matters:** This is a fundamental challenge for the adoption of agentic forecasting in production environments where cost-efficiency and robust statistical validation are prerequisites.