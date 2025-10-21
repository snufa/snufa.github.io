# Robustness of Spike-Based Computations Across Temporal Resolutions

**Authors:** Prakriti Parthasarathy, Timothy O'Leary
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking neural networks (SNNs) are widely regarded as biologically plausible models of neural computation. However, they remain approximations of the brain’s continuous-time (CT) dynamics implemented on inherently discrete-time (DT) hardware and software. This CT–DT mismatch raises two questions: 1. How does discretisation affect both single-neuron and network-level dynamics, and 2. How to accurately preserve neuronal and synaptic dynamics across temporal resolutions. In particular, the choice of simulation timestep dt and discretisation strategy directly impact not only the temporal fidelity but also the stability and reproducibility of spike-based computations across platforms and timescales.

In this work, we systematically examined different discretisation strategies- Euler’s Forward, Zero-Order Hold, and Impulse Invariance- applied to standard leaky integrate-and-fire (LIF) units, revealing how each method introduces distinct dynamics and how the temporal resolution dt modulates these effects. Consequently, we derived rescaling factors to maintain consistent neuronal responses across different dts, providing a principled approach to preserving dynamics while transforming a spiking system from CT to DT. We then extended these findings to SNNs trained on benchmark classification tasks (rate-coded MNIST with surrogate gradient descent), to analyse how timestep choices influence learning, representation formation, and the transferability of trained models across temporal resolutions.

Our results show that although good performance in SNNs can be achieved for a fixed timestep, performance is not robust to changes in timestep. Most crucially, training SNNs with surrogate gradients results in networks whose performance degrades as dt->0. These findings highlight the fundamental role of temporal granularity in current approaches for SNN simulation and training, and emphasise the need for systematic methods to ensure consistency and reproducibility across heterogeneous SNN implementations. 
