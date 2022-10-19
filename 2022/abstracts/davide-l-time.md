
# Time Series Forecasting with Spiking Neural Networks

**Authors:** Davide L. Manna

**Presentation type:** Poster

## Abstract

Analysing time series data is critical in applications as diverse as demand forecasting and speech recognition. In the Neuromorphic (NM) computing field, the time dimension is embedded in the mechanisms and algorithms that constitute its core; however, very little research has been done on time-series forecasting. Furthermore, time series data could represent a valid benchmark to evaluate NM algorithms and Spiking Neural Networks (SNNs) as an alternative to other datasets that are often argued as not having time-relevant features.
In this work, we propose a pipeline based on a novel event camera-inspired data encoding mechanism for time series data, a novel loss function, and an SNN featuring different spiking neuron models. We consider Sigma-Delta (?-?) neurons, Resonate-and-Fire (R&F), and Current Based (CuBa) Leaky Integrate-and-Fire (LIF) neuron models and compare the resulting SNNs to a conventional CNN with the same topology and trained on the same task. As a sample dataset, we use the Appliances Energy Prediction dataset and focus on the energy recordings of Appliances only, thus obtaining a univariate forecasting problem. Experimental results show that in all cases, the SNNs demonstrate the ability to successfully predict future changes in trends as either increasing or decreasing. Collectively, our results highlight that SNNs can successfully perform predictions on time series data, with the advantage of enabling low-power and low-latency computations, hence highlighting how further investigations and optimisations to solve this family of tasks would be beneficial.
