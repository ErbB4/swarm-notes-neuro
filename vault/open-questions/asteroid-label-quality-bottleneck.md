---
created_at: '2026-05-15T06:16:06Z'
source_papers:
- '[[openalex-260512391-trajectory-agnostic-asteroid-detection-in-tess-with-deep-lea]]'
title: Moving Object Label Quality Bottleneck
---

**Background:** Machine learning models for moving object detection in astronomical time-series rely on ground-truth labels derived from existing, often incomplete, catalogs.

**Question / Future Work:** The accuracy and completeness of ground-truth labels used for training machine learning models for asteroid detection represents a significant bottleneck. Improving these labels, or developing semi-supervised methods that account for label noise or incompleteness, is necessary to improve detection reliability for faint objects.

**Why It Matters:** This is a foundational performance bottleneck for supervised learning in astronomical surveys.

**Evidence:** The impact this has on our model is effectively self-limitation... the performance of our model... will be inherently limited by the completeness and accuracy of the asteroid data used for training.