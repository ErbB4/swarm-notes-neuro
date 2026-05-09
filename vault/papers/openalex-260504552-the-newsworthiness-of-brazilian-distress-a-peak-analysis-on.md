---
# CSL-compatible fields
title: "The Newsworthiness of Brazilian Distress: A Peak Analysis on Time Series of International Media Attention to Disasters in Brazil"
author:
  - literal: "Brielen Madureira"
  - literal: "Andreas Niekler"
  - literal: "Marc Keuschnigg"
  - literal: "Mariana Madruga de Brito"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04552"

# Custom fields
paper_id: "2605.04552"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:57:27Z"
created_at: "2026-05-09T05:57:27Z"
---

# The Newsworthiness of Brazilian Distress: A Peak Analysis on Time Series of International Media Attention to Disasters in Brazil

**Authors**: Brielen Madureira, Andreas Niekler, Marc Keuschnigg, Mariana Madruga de Brito
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04552](https://arxiv.org/abs/2605.04552)

## Summary

This paper investigates the drivers of international media attention towards disasters in Brazil by analyzing a 24-year collection of German news reports. The authors employ time series segmentation to isolate specific news event peaks and correlate them with objective disaster records. The study provides insights into the disparity between local disaster impact and international news visibility, offering a systematic framework for future media attention research.

## Key Contributions

- Introduces a peak analysis methodology for identifying international media attention surges regarding Brazilian disasters.
- Constructs a long-term (2000–2024) dataset of 2,000 news articles from German media concerning Brazilian fires and landslides.
- Evaluates the temporal alignment between international media attention peaks and official national or global disaster database records.

## Open Questions & Future Work

- [[aligning-news-disaster-databases]]

## Archivist Review

I have approved the open question regarding the alignment of media event data with ground-truth disaster databases, as this highlights a fundamental bottleneck in socio-technical time series analysis. I rejected the concept candidate because 'peak analysis' is a generic analytical technique, and I rejected the dataset due to its limited scale and narrow domain.

### Approved Open Questions
- Aligning News With Disaster Databases: Without precise alignment, it is impossible to accurately assess the representativeness of news-based datasets or understand the specific disaster characteristics that trigger international media attention versus local bureaucratic registration.

### Rejected Candidates
- [concept] Peak Analysis Methodology (`peak-analysis-methodology`) - not_novel: The methodology described is a standard analytical approach for time series segmentation rather than a novel, reusable ML-specific technique.
- [dataset] German-Brazilian Disaster News Dataset (`german-brazilian-disaster-news-dataset`) - low_impact: The dataset is relatively small (2k articles) and domain-specific, lacking the broad utility required for a permanent vault note.

## Links

- [Abstract](https://arxiv.org/abs/2605.04552)
- [PDF](https://arxiv.org/pdf/2605.04552)

