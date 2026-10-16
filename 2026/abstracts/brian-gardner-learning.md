# Learning part-whole relationships through polychronization in a hierarchical spiking network

**Authors:** Brian Gardner, Patrick McCarthy, Joseph Chrol-Cannon, Dan Goodman, Simon Schultz, Giovanni Lo Iacono, Simon Stringer
                           


**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

How the brain represents hierarchical relationships between visual features, such as a local contour forming part of a larger one, is central to the feature binding problem and remains a conceptual challenge in neuroscience. Binding by polychrony proposes that such part-whole relationships are encoded by polychronous groups, whose neurons fire in repeating, time-locked but asynchronous sequences supported by heterogeneous conduction delays. In a minimal binding circuit, a low-level feature neuron projects to a high-level feature neuron, and both project to a binding neuron; with matched delays, their spikes coincide at the binding neuron only when the low-level neuron helps drive the high-level one. Accordingly, the circuit's time-locked firing encodes their hierarchical relationship.

We tested whether such circuits emerge in a four-layer spiking network inspired by the primate ventral stream, comprising feedforward, feedback and lateral connections, receptive fields widening with depth, and fixed, heterogeneous axonal delays. Through unsupervised competitive learning via spike-timing-dependent plasticity during exposure to related 2D shapes, neurons became selective for individual boundary elements, with higher layers integrating lower-layer fragments into larger contours. Despite randomised, Poisson-distributed input spike timings, statistically tested pattern detection revealed recurring spike patterns matching the minimal circuit's connectivity and delays. These were rare before learning, and some became highly selective (F1 > 0.9) for specific object features.

For more complex shapes, circuits outnumbered neurons in the higher layers, so neurons were reused, often in different roles. Reuse did not reduce selectivity: a circuit's F1 score was essentially independent of how many features its binding neuron served, and about 40% of highly selective final-layer circuits had a binding neuron that did not itself identify the bound feature. This supports a circuit-level code in which time-locked co-firing, not dedicated binding cells, carries each relationship, potentially letting spiking networks represent more relationships than they have neurons.