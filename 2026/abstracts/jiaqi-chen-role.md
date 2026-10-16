# Role of axo-axonic synapses in Drosophila sensory processing

**Authors:** Jiaqi Chen, Daniel Han, Albert Cardona
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

A newly reconstructed connectome of the Drosophila larva shows that the canonical axo-dendritic synapse is not the default: it accounts for only 66% of all synapses, with axo-axonic connections comprising the majority of the remainder. Yet axo-axonic synapses are ignored by most existing spiking models of connectomes, which treat every synapse as if it terminated on the dendrite, despite electrophysiological evidence throughout vertebrates and invertebrates showing depolarising currents onto the axon to have an inhibitory rather than excitatory effect on spike output.

We built a two-compartment extension of Eugene Izhikevich's (2003) spiking neuron model that models axonic inputs based on the electrophysiological data, and applied it to reconstructed larval visual and olfactory circuits. Under single-compartment leaky-integrate-and-fire and Izhikevich formulations, treating axo-axonic inputs as axo-dendritic drives circuits into runaway excitation, forcing unrealistically low synaptic weights during fitting. The two-compartment model abolishes this runaway excitation at negligible extra computational cost, scaling no worse than a single-compartment model with the number of neurons.

Normalisation is central to information processing in both the larval optic and antennal lobes, achieved through motifs such as feedforward and lateral inhibition. The two-compartment model reveals axo-axonic-mediated inhibition as an additional source of normalisation in both circuits, and robustly recovers its role in maintaining system sensitivity across the many orders of magnitude of stimulus intensity that real Drosophila systems encounter. Together, these findings suggest that receptor-neuron-to-inhibitory-interneuron axo-axonic connections are a previously unnoticed circuit motif for sensory normalisation.

These results argue that axo-axonic synapses are not a connectomic curiosity but a computational necessity, and that two-compartment models are needed to correctly interpret the wiring diagrams that whole-brain connectomes now provide.