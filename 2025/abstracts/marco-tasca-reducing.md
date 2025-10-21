# Reducing computational cost in spiking networks with a periodic reset model

**Authors:** Marco Tasca, Julia Gygax, Friedemann Zenke
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking neural networks (SNNs) offer energy-efficient, event-driven computation. However, while membrane potential updates of leaky integrate-and-fire (LIF) neurons are efficient on analog neuromorphic hardware, this is not necessarily the case when simulated on digital substrates. The choice of neuron model can therefore dramatically reduce the number of floating-point operations. To address that, we developed the periodic integrate-and-fire (PIF) neuron, which replaces the expensive double exponential kernel of LIF neurons with perfect integration and a periodic reset of the membrane potential.

To improve model training, we relied on several strategies. First, we initialized PIF reset periods from a gamma distribution, mimicking the heterogeneous initialization of time constants proven successful in LIF neurons. Second, we derived a PIF-specific fluctuation-driven initialization strategy to stabilize training for the non-leaky PIF dynamics. Finally, we applied different pruning methods to compare how well the models scale under sparsity: (1) synapse pruning by magnitude; (2) neuron pruning by gradient; (3) neuron pruning by criticality.

We evaluated PIF against LIF neurons on the Spiking Heidelberg Digit classification task at inference, and assessed computational cost based on effective floating-point operations (EFLOPs). Results showed a reduction of up to 40% in EFLOPs at the optimal tradeoff, while maintaining similar accuracy (PIF: 73% ± 2%, LIF: 72% ± 1%). Gains were especially large for networks with many neurons. We further found that (i) heterogeneity in temporal parameters benefits PIF neurons as it does for LIFs; (ii) PIF-specific fluctuation-driven initialization is crucial for stable training; and (iii) criticality-guided neuron pruning scales best for compressing SNNs, while synapse pruning consistently preserves PIF neurons’ superior efficiency. 

In conclusion, PIF neurons offer a simple, hardware-friendly approach to reduce computational cost in SNNs.