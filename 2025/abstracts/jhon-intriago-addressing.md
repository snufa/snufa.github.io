# Addressing the Comparability Crisis in Adaptive SNNs

**Authors:** Jhon Intriago, Pablo A. Estévez
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

The rapid evolution of Adaptive Spiking Neural Networks (ASNNs) is impeded by issues related to comparability. We find that reproducing and comparing state-of-the-art results is difficult due to inconsistent protocols and subtle data handling differences.

The core problem lies in data fidelity and optimization integration. First, regarding Spike Data Fidelity and Representation, many SNN libraries use data representations that are not true, spike events. Instead, they represent accumulated, collapsed values within sparse tensor formats. This fundamentally alters the dynamics, leading to learning that is not genuinely spike-based and invalidating direct performance comparisons between models trained on true versus collapsed spike streams. Second, optimization techniques (e.g., RAdam, custom learning rules) are often integrated without proper ablation, making it impossible to isolate the actual contribution of the proposed ASNN method. Third, regarding Protocol Inconsistency, variables like time-step resolution (Δt) and sequence length are rarely controlled across papers, further decoupling results.

For reliable scientific benchmarking, we propose Standardized Evaluation Rules. In terms of Transparency, explicitly disclose the spike data representation used (discrete events vs. accumulated values). For Ablation study, mandatory systematic comparison that isolates a novel method's gain from the effects of the optimizer and data encoding. Finally, for Baseline Control, use identical hyperparameter settings when comparing against simple, established baselines (e.g., standard LIF, BRF, ADLIF neuron models).

We advocate for mandatory code release and transparent data-handling protocols to enable reliable, cumulative progress in the SNNs models.
