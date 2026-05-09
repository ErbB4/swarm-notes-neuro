---
# CSL-compatible fields
title: "Event-Based Early Warning of Vineyard Disease Risk from Environmental Time Series"
author:
  - literal: "Ivica Dimitrovski"
  - literal: "Ivan Kitanovski"
  - literal: "Danco Davcev"
  - literal: "Slobodan Kalajdziski"
  - literal: "Kosta Mitreski"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04548"

# Custom fields
paper_id: "2605.04548"
paper_source: "openalex"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "event-based-early-warning-protocol"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:57:21Z"
created_at: "2026-05-09T05:57:21Z"
---

# Event-Based Early Warning of Vineyard Disease Risk from Environmental Time Series

**Authors**: Ivica Dimitrovski, Ivan Kitanovski, Danco Davcev, Slobodan Kalajdziski, Kosta Mitreski
**Date**: 2026-05-06
**Paper ID**: [openalex:2605.04548](https://arxiv.org/abs/2605.04548)

## Summary

This paper introduces an event-based framework for vineyard disease risk prediction, shifting focus from daily status classification to detecting transitions into risk windows. By requiring a minimum disease-free gap to define new events, the approach mitigates persistence bias and encourages the learning of environmental precursors. Experiments using multi-year agro-meteorological data demonstrate the efficacy of this formulation across XGBoost, LSTM, and TCN models, highlighting the critical role of task design in agricultural early warning systems.

## Key Contributions

- Reformulates vineyard disease risk prediction from daily binary classification to an event-based task, targeting transitions into risk periods within a 3-7 day window.
- Introduces a duration-based event definition that suppresses label fragmentation caused by short-term environmental noise.
- Demonstrates that classical models like XGBoost and deep models like LSTM/TCN provide distinct trade-offs between recall, lead time, and false-alert rates under an event-oriented evaluation protocol.

## Open Questions & Future Work

- [[multi-site-generalization-disease-warning]]

## Key Concepts

- [[event-based-early-warning-protocol]]: A problem formulation that shifts time-series prediction from daily status classification to identifying transitions into risk periods, mitigating persistence-driven artifacts.

## Archivist Review

The paper makes a notable methodological contribution by reformulating time-series classification as an event-based transition detection task to avoid persistence bias. The approved concept and open question highlight this shift and the subsequent challenge of generalizability, which are central to the future of robust, operational environmental forecasting. I rejected the label validation question as it is a dataset-specific concern regarding proxy labels rather than a systemic modeling bottleneck.

### Approved Concepts
- Event-based early warning protocol: This approach reframes environmental forecasting from persistence-prone classification to transition detection, enabling more actionable, precursor-aware decision support in high-stakes domains.

### Approved Open Questions
- Multi-site Generalization in Warning Systems: Establishing cross-site transferability is a prerequisite for moving from localized proof-of-concept models to robust, widespread operational decision support systems.

## Links

- [Abstract](https://arxiv.org/abs/2605.04548)
- [PDF](https://arxiv.org/pdf/2605.04548)

