---
created_at: '2026-05-09T05:57:27Z'
source_papers:
- '[[openalex-260504552-the-newsworthiness-of-brazilian-distress-a-peak-analysis-on]]'
title: Aligning News With Disaster Databases
---

**Background:** Computational methods for analyzing disaster coverage often struggle to reliably align international news reports with official disaster database entries due to differences in reporting criteria and geographic precision.

**Question / Future Work:** There is an unresolved need for refined methods to improve the temporal and content alignment between news-based event detection and existing disaster databases (e.g., EM-DAT, S2iD). Current approaches frequently suffer from misalignments, particularly when news reports discuss aggregated disaster impacts over time, whereas databases record distinct events at specific times and locations. Future work should explore techniques such as reverse top-down news selection, where disaster metadata is used to generate targeted queries, and robust geolocation of news toponyms to achieve higher confidence in matching news events to physical disaster occurrences.

**Why It Matters:** Without precise alignment, it is impossible to accurately assess the representativeness of news-based datasets or understand the specific disaster characteristics that trigger international media attention versus local bureaucratic registration.

**Evidence:** For S2iD, temporal alignment is not enough. Refined methods to avoid misalignments are e.g. a reverse top-down news selection approach using the disaster metadata to create targeted queries for the news database and matching location toponyms for more certainty.