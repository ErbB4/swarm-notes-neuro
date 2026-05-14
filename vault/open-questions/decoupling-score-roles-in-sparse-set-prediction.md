---
created_at: '2026-05-14T06:09:48Z'
source_papers:
- '[[openalex-260510298-set-prediction-for-next-day-active-fire-forecasting]]'
title: Decoupling Score Roles in Set Prediction
---

**Background:** Wildfire forecasting involves predicting discrete, localized fire events which are often sparse and occur across heterogeneous spatial and temporal scales. Current models predominantly focus on dense, gridded fire-probability or danger scores, which struggle to represent these sparse events.

**Question / Future Work:** A core challenge in sparse set prediction for wildfires is the score-role conflict where the same predicted fire probability simultaneously influences bipartite matching, ranking, and query activation. While bipartite matching helps bridge the gap between fixed-query sets and variable-length target sets, it remains unclear how to best decouple these conflicting roles, particularly in ensuring both accurate localization and stable, well-calibrated confidence ranking during inference. Future research is needed to develop more robust assignment mechanisms and training objectives that explicitly decouple these roles.

**Why It Matters:** Decoupling these roles is essential for achieving reliable uncertainty estimation and avoiding issues such as duplicate detections or poor ranking of predicted fire queries, which are critical for the operational use of wildfire forecasts in disaster management.

**Evidence:** we identify a score-role conflict specific to sparse wildfire set prediction, where the same score affects assignment, ranking, and query activation