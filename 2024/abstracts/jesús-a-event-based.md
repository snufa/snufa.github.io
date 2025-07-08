# Event-Based Eligibility Propagation with Additional Biologically Inspired Features

**Authors:** Agnes Korcsak-Gorzo, Jonas Stapmanns, Jesús A. Espinoza Valverde, Hans Ekkehard Plesser, David Dahmen, Matthias Bolten, Sacha J. van Albada, Markus Diesmann
                           
**Presenting author:** Jesús A. Espinoza Valverde

**Presentation type:** Flash talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Understanding how neural circuits learn is crucial for advancements in both neuroscience and artificial intelligence. While traditional methods such as backpropagation through time (BPTT) are widely used to study learning processes in neural networks,  they are not biologically plausible. A biologically inspired alternative, eligibility propagation (e-prop), has been proposed by Bellec et al. (2020), offering performance that more closely approximates BPTT.

We introduce bio-inspired modifications to the e-prop algorithm that maintain learning performance while enhancing biological accuracy. Additionally, we reformulate the original model's time-driven update routine by adopting an event-driven approach. Instead of updating synaptic states at every time step, our method updates them only when a spike is transmitted, significantly improving computational efficiency. This is particularly effective in simulations of biologically realistic, sparsely connected spiking neural networks (SNNs). Our modifications, implemented in NEST, a leading simulator for large-scale SNNs, demonstrate robust scalability in extensive network simulations.

These advancements bridge the gap between computational efficiency and biological realism, significantly enhancing e-prop's applicability in large-scale and biologically plausible spiking neural network simulations.