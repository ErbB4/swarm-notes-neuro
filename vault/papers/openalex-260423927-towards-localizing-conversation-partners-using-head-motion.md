---
# CSL-compatible fields
title: "Towards Localizing Conversation Partners using Head Motion"
author:
  - literal: "Payal Mohapatra"
  - literal: "Calvin Murdock"
  - literal: "Ali Aroudi"
  - literal: "Ishwarya Ananthabhotla"
  - literal: "Anjali Menon"
  - literal: "Buye Xu"
  - literal: "Morteza Khaleghimeybodi"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.23927"

# Custom fields
paper_id: "2604.23927"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "acoustic-zone-localization"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T06:05:23Z"
created_at: "2026-04-30T06:05:23Z"
---

# Towards Localizing Conversation Partners using Head Motion

**Authors**: Payal Mohapatra, Calvin Murdock, Ali Aroudi, Ishwarya Ananthabhotla, Anjali Menon, Buye Xu, Morteza Khaleghimeybodi
**Date**: 2026-04-27
**Paper ID**: [openalex:2604.23927](https://arxiv.org/abs/2604.23927)

## Summary

This paper addresses the challenge of enhancing speech in noisy environments by proposing a wearable-based approach to identify a user's acoustic zone of interest. The authors introduce HALo, a network that leverages IMU data from smartglasses to infer conversational partner locations, and CoCo, a partner-counting classifier. Together, these systems improve localization performance by 21% and enable more effective end-to-end speech enhancement compared to traditional, audio-only spatial methods.

## Key Contributions

- Introduced HALo, a network that localizes acoustic zones of interest using smartglasses' IMU data, achieving a 21% performance improvement over existing spatial audio methods.
- Introduced CoCo, an IMU-based classifier for the number of conversation partners, outperforming baseline models by 35% with 0.74 accuracy.
- Demonstrated that head-orientation-based localization enables effective speech enhancement in challenging, noisy environments with multiple speakers.

## Open Questions & Future Work

- [[dynamic-acoustic-zone-localization-bottleneck]]

## Key Concepts

- [[acoustic-zone-localization]]: The process of using wearable sensor data, such as IMU head-orientation, to infer a user's focus of auditory attention in multispeaker environments.

## Archivist Review

The paper introduces a novel application of wearable IMUs for acoustic zone identification. I have abstracted the specific architectures (HALo and CoCo) into a more fundamental concept of 'Acoustic Zone Localization' and identified a bottleneck regarding the dynamic nature of conversational environments as the key open research challenge. I rejected the model-specific names to ensure the vault remains focused on reusable methodological concepts.

### Approved Concepts
- Acoustic Zone Localization: Provides a foundational mechanism for bridging wearable behavioral sensor data with spatial audio enhancement, a key challenge in hearable technology.

### Approved Open Questions
- Dynamic Acoustic Zone Localization: This is the primary constraint preventing wearable-based audio enhancement from being deployed in unstructured, real-world social environments.

### Rejected Candidates
- [concept] HALo (`halo-network`) - subcomponent_of_broader_mechanism: This is a specific model architecture instance; the broader mechanism is acoustic zone localization.
- [concept] CoCo (`coco-partner-counting`) - subcomponent_of_broader_mechanism: This is a specific task/implementation submodule rather than a foundational methodology.
- [open_question] Dynamic Conversation Partner Localization (`dynamic-conversation-partner-localization-behavioral-cues`) - duplicate_existing: The title and background were wordy and redundant; a more concise, systemic bottleneck was formulated.

## Links

- [Abstract](https://arxiv.org/abs/2604.23927)
- [PDF](https://arxiv.org/pdf/2604.23927)

