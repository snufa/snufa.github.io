# Novel Deep-RL Method for Three-Factor Based Automata

**Authors:** Michael Tarlton
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Deep learning is limited by the current popular method of credit-assignment Back-Propagation (BP). BP is impossible to utilize in deep non-linear architectures as found in the brain. BP is also difficult to implement in Spiking Neural Networks (SNNs), and many methods of applying such are not native to spiking-dynamics. To take full advantage advantage of SNN models, we need better methods of credit-assignment, methods directly designed for spiking systems.

As spiking communication is inherently time-based, we may be able to adapt known models of temporal dynamics and learning in the brain for new methods of credit-assignment for SNNs. Time may add a dimension for triangulating credit-assignments to neurons in deep and otherwise unnavigable systems.

Studying the interplay of timing properties at the fundamental spike-firing (<10-100ms) range and the emergent sub-to-suprasecond (>100-1000ms) range may reveal how sub-population dynamics organize into population time representations. I.e.: How do the time dynamics of one scale emerge into time dynamics at higher scales?

We have adapted a neuroscientific model of timing, the Striatal Beat Frequency (SBF) model as a naïve neural automata: the SBF-A. The minimal SBF-A circuit consists of oscillatory nodes whose activity projects to a three-factor learning neuron. As the SBF-A operates in an online RL environment, the learning node encodes internal time representations by redistribution of weight over the incoming synapses. This minimal model is capable of learning, representing, and reproducing external time-events.

  We expand the SBF-A into a multi-neuronal, multi-layer network,  capable of learning and reproducing complex time representation in timing-based tasks.  We will present this as a novel method of Deep-RL for networks with deep and recurrent topologies, and with the capability to scale with network size.
