# A feedback control algorithm for online learning in Spiking Neural Networks and Neuromorphic devices

**Authors:** Matteo Saponati, Chiara De Luca, Giacomo Indiveri, Benjamin Grewe
                           
**Presenting author:** Matteo Saponati

**Presentation type:** Talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

The success of Artificial Neural Networks (ANNs) trained with backpropagation depends on offline training, large datasets, and energy-intensive simulations. In contrast, biological neurons learn quickly and efficiently using local networks, dendritic segregation, and self-supervised learning rules. Inspired by these mechanisms, spike-based learning circuits have been developed for Spiking Neural Networks (SNNs), particularly useful for neuromorphic devices that excel in low-latency, low-power computations. However, these bio-inspired methods are limited in their expressivity and efficiency, especially for complex, real-world tasks.

To overcome these limitations, we propose a novel learning framework for SNNs that combines spike-based local learning with control feedback signals. The algorithm operates locally and does not require backpropagating gradients, allowing online learning in SNNs and Neuromorphic devices.  We validate this framework on different datasets and neuromorphic hardware simulations, demonstrating its potential for efficient training despite device mismatches.

In conclusion, this study introduces a novel learning framework for SNNs that strengthens the links between biologically inspired learning and neuromorphic computing. The empirical validation of this method across various datasets and its effective behavioral simulations on neuromorphic hardware demonstrate its potential to revolutionize the scalability of neuromorphic devices.