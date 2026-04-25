---
created_at: '2026-04-25T05:37:17Z'
source_papers:
- '[[openalex-260420072-vertex-misalignment-and-changepoint-localization-in-network]]'
title: Classifying Changepoint Signal Location
---

**Background:** When analyzing dynamic networks, the choice between using marginal distributions or joint distributions for changepoint localization often depends on the specific structure of the underlying latent position process. Real-world network data frequently exhibits properties that fall between theoretical edge cases where marginal information is sufficient versus those where joint information is essential.

**Question / Future Work:** There is a need to develop a principled method for distinguishing whether the primary changepoint signal in a network time series resides in the marginal or the joint distribution of latent positions. Furthermore, constructing and analyzing intermediate latent position process models that capture behaviors observed in complex empirical data—where signal is lost after vertex shuffling but partially recoverable through graph matching—remains a significant open problem.

**Why It Matters:** This is technically critical because existing changepoint detection methodologies perform significantly differently depending on whether they rely on marginal or joint information. Understanding how to handle intermediate cases is essential for robust inference in real-world applications where the nature of the signal is unknown.

**Evidence:** It is unclear whether these additional detected changepoints are spurious, or just subtler than the ones detected by eye. ... This raises the question of whether we can construct intermediate cases, where the signal is contained in both marginal and joint information, and finding appropriate distances for measuring the dynamics in such cases.