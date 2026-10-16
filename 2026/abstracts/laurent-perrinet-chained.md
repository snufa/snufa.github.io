# Chained Neural Delays for Extended Temporal Pattern Tracking

**Authors:** Laurent Perrinet
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

How do neurons with millisecond-scale memory track patterns unfolding over seconds? While biological brains process information across vast timescales, individual neurons store incoming spikes for only a few milliseconds. We bridge this gap by augmenting Leaky-Integrate-and-Fire (LIF) neurons with heterogeneous synaptic delays, enabling the detection of elementary spiking motifs with millisecond precision. To scale this mechanism to systemic timescales, we then employ a recurrent population of such neurons, trained to read sequences of motifs and predict subsequent spikes, thereby forming "temporal chains". By combining both a rigorous analytical initialisation with supervised learning via surrogate gradients as implemented using  snnTorch, the network learns to track and replay extended temporal patterns spanning several seconds.
The versatility of this architecture is demonstrated across increasing levels of complexity: from the precise reconstruction of synthetic patterns to the modelling of travelling waves on a cortical surface and the simulation of complex dynamics evolving on a manifold. Remarkably, we extend this framework to text generation, treating symbolic sequences as high-level temporal patterns. Our results suggest that chained heterogeneous delays provide a biologically plausible implementation of dynamic associative memory, offering a computationally efficient substrate for bridging the divide between millisecond cellular storage and temporal recognition on the scale of seconds.