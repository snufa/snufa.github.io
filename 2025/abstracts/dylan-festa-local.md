# A local homeostatic STDP rule for stable dynamics and stimulus selectivity in recurrent spiking neural networks

**Authors:** Dylan Festa, Claudia Cusseddu, Divyansh Gupta, Julijana Gjorgjieva 
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Compared to rate-based models, spiking neural networks (SNNs) provide a more complex but biologically plausible model of neural circuits. Synaptic plasticity mechanisms in SNNs—such as spike-timing-dependent plasticity (STDP)—adjust synaptic weights based on the precise timing of pre- and post synaptic spikes, capturing local interactions at very short timescales. However, classic Hebbian STDP alone does not ensure convergence of weights, and typically requires additional control mechanisms, such as hard-bounds or synaptic normalization. This often introduces additional complexity to the system, sometimes involving global variables and non-local operations. Here, we propose a simple, local plasticity rule based on the same principles of STDP that promotes circuit stability while circumventing these limitations.

Specifically, we model synaptic changes as the result of two interacting components: a classic STDP term, driven by both the pre- and the postsynaptic activity, and a multiplicative homeostatic term, driven solely by the postsynaptic activity. While the classic STDP term promotes Hebbian learning and shapes the connectivity structure, the latter acts as a broader self-regulatory term, triggered by imbalances in the neuron’s firing rate.

The simplicity of the proposed rule allows us to analytically understand the distinct contributions to synaptic changes given by firing rates, STDP kernel, and the covariance between pre- and postsynaptic activity. Our analytical predictions are validated through numerical simulations. Moreover, when applied to recurrent SNNs, this rule promotes stimulus selectivity and self-stabilization of network dynamics. Hence, our newly proposed STDP-based homeostatic scaling mechanism ensures circuit stability through purely local interactions, without interfering with learning and emergent structure.