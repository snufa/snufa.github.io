---
youtube: 0G7vHD4M3WI?si=lJqxOIuT3WjMP2EE
---
# Space as Time Through Neuron Position Learning

**Authors:** Balázs Mészáros, James C. Knight, Thomas Nowotny, Danyal Akarca
                           


**Presentation type:** Talk at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Brain networks face fundamental trade-offs between metabolic cost and information processing capacity. They must minimise the expense of building and maintaining connections in physical space while optimising computational efficiency. These constraints shape brain organisation across species and may explain the convergence on sparse, small-world, and modular architectures. Yet most computational models overlook a critical factor: the spatial embedding of biological neural networks and its direct link to temporal processing.
We embed neurons into a D-dimensional Euclidean space, and define synaptic delays by pairwise distances. We then derive gradients with respect to neuron positions within the EventProp formalism and study the resulting network geometries and topologies after training networks on classification tasks. Networks with learned positions achieve comparable performance to networks with unconstrained delay matrices, but with a significantly reduced parameter count (N×D vs. N×N, where N is the number of neurons and D the embedding dimension). The constrained delay distributions also encourage networks to develop more "local" representations, relying predominantly on short-range connections and producing modular, small-world topologies. Introducing a cost for long-distance connections by pruning based on connection length yields classification performance similar to typical weight magnitude based pruning, but results in topologies and geometries more consistent with brain-like wiring principles.