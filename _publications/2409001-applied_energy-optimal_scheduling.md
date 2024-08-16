---
title: "Optimal scheduling of renewable energy microgrids: A robust multi-objective approach with machine learning-based probabilistic forecasting"
collection: publications
category: manuscripts
permalink: /publication/2409001-applied_energy-optimal_scheduling
excerpt: 'This work presents an innovative approach that incorporates ML probabilistic forecasting into rolling horizon strategies for the economic dispatch - unit commitment  problem, which are two techniques not often merged in the current state of the art.'
date: 2024-09-01
venue: 'Applied Energy'
slidesurl: 'https://doi.org/10.1016/j.apenergy.2024.123548'
paperurl: 'https://doi.org/10.1016/j.apenergy.2024.123548'
citation: 'D. Aguilar, J. Quinones, L. Pineda, J. Ostanek, L. Castillo. (2024). &quot;Optimal scheduling of renewable energy microgrids: A robust multi-objective approach with machine learning-based probabilistic forecasting.&quot; <i>Applied Energy</i>.'
---

Abstract:
Microgrids (MGs) powered by renewable energy sources (RES) like solar and wind face integration and management challenges due to their variability and fluctuating energy prices. Moreover, traditional scheduling strategies often overlook the decay in prediction accuracy over time and lack a mechanism for establishing optimal forecasting horizons. This research addresses this gap by merging machine learning (ML) probabilistic forecasting with robust optimization to create optimal dispatch schedules for RES MGs. It reveals that longer scheduling horizons can reduce dispatch costs but at the expense of forecast accuracy due to increased prediction accuracy decay (PAD). To address this, we propose a novel method that determines how to split the time horizon into timeblocks to minimize dispatch costs and maximize forecast accuracy. This forms the basis of an optimal rolling horizon strategy (ORoHS) which schedules distributed energy resources over varying prediction/execution horizons. The model was evaluated on a simulated renewable microgrid with energy storage. Probabilistic forecasts were generated for wind, solar, and energy prices at different confidence levels. This data fed into a robust optimization model to schedule energy transactions. Results offer Pareto-optimal fronts, showing the trade-offs between cost and accuracy at varying confidence levels. Solar power proved more cost-effective than wind power due to lower variability, despite wind’s higher energy output. The ORoHS strategy outperformed common scheduling methods. In the case study, it achieved a cost of $4.68 compared to $9.89 (greedy policy) and $9.37 (two-hour RoHS).

Highlights:
- Novel rolling horizon strategy optimally splits time horizon for cost and accuracy
- Probabilistic forecasts enable robust RES MG scheduling under uncertainty
- RES variability leads to trade-off between prediction accuracy and dispatch costs.
- Solar forecasts allow longer, cheaper schedules despite lower power output.
