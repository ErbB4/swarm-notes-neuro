---
created_at: '2026-05-17T06:08:44Z'
source_papers:
- '[[openalex-260514227-dt-transformer-a-foundation-model-for-disease-trajectory-pre]]'
title: Long-horizon clinical forecasting decay
---

**Background:** Disease trajectory models often suffer from performance decay over longer prediction horizons when trained on structured electronic health record data, which is typically organized around episodic clinical encounters rather than continuous patient timelines.

**Question / Future Work:** Future research is needed to explore whether multi-token prediction objectives—adapted from language modeling—can mitigate temporal signal attenuation and improve performance on extended prediction horizons in clinical settings.

**Why It Matters:** This addresses a core bottleneck in the deployment of foundation models for disease progression, where long-term clinical utility depends on maintaining predictive accuracy beyond the next immediate event.