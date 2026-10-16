# Deriving, learning, and understanding heterogeneous spike coding networks

**Authors:** Stefan Iacob, Sander Keemink, Fleur Zeldenrust
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

In both real brains and neuromorphic chips, the properties of nodes show strong heterogeneity. However, the mechanism behind how continuous information can be encoded using discrete spikes in a heterogeneous neural substrate is still unknown. To answer this question, it is key to understand how heterogeneity interacts with spike coding.

Spike Coding Networks (SCNs) have been proposed as a strategy to find the optimal connectivity of spiking neural networks (SNNs), ensuring a balance between high encoding accuracy and low spike frequency (efficiency). SCNs have several interesting properties including EI balance, robustness against noise and neuron loss, and a high trial-to-trial variability despite millisecond precision. Most importantly, SCN theory offers a clear interpretation of the role of membrane potentials as errors and spikes as error corrections. 

Conventional SCNs so far do not account for the heterogeneity of biological or neuromorphic networks. To maintain a correct internal error representation, they require precisely selected network parameters. This includes synaptic weights, membrane time constants, and synaptic time constants. SCNs are built on the assumption that all membranes and synapses have the same filtering time constant. Deviating from this assumption leads to a drifting or incoherent error representation. This reliance on homogeneous timescales in SCNs limits their biological relevance, as well as their use for neuromorphic computing, as perfect consistency in manufacturing is difficult to guarantee.

In this work, we extend SCN theory to allow for heterogeneous timescales, in both membranes and in synapses. We first provide an analytically derived method to obtain optimal recurrent connectivity for heterogeneous populations of spiking neurons. Next, we provide a local learning rule to find and maintain these optimal weights starting from random connectivity. We conclude that such heterogeneous SCNs learn to maintain a correct internal error representation, without relying on an explicit global error signal.
