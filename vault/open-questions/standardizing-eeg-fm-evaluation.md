---
created_at: '2026-05-17T06:08:07Z'
source_papers:
- '[[openalex-260514698-neuroatlas-benchmarking-foundation-models-for-clinical-eeg-a]]'
title: Standardizing EEG-FM Evaluation Protocols
---

**Background:** Foundation models for EEG are typically benchmarked on individual datasets or single tasks, which obscures their true cross-dataset and cross-domain generalization capabilities.

**Question / Future Work:** Current evaluation protocols for EEG foundation models lack consistency in downstream task selection and often fail to isolate the contribution of pretraining from that of the downstream architecture. There is a need for robust, standardized benchmarks that use multiple datasets per clinical domain and employ clinically grounded metrics to determine if these models provide genuine utility over specialized supervised models or generic time-series foundation models.

**Why It Matters:** Understanding whether EEG foundation models provide intrinsic value or simply memorize training data is crucial for their reliable deployment in clinical decision support systems.

**Evidence:** Existing evaluations give an incomplete answer. Most benchmarks reduce each domain to a single dataset, a single metric, and a single family of models... leaving three central aspects of EEG-FM behavior untested.