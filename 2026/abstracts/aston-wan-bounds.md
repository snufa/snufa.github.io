# Bounds for Universal Representation with Spiking Neural Networks

**Authors:** Aston Wan, Evan Zhao, Nathan Yan
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Spiking neural networks (SNNs) are an energy-efficient alternative to conventional neural networks, but their theoretical expressive power is far less understood. In this paper, we examine Leaky Integrate-and-Fire (LIF) networks as function representors, where each input is a boolean sequence of length $T_{in}$, and the output is a single bit. We ask how many non-input neurons are required to represent an arbitrary boolean function from such inputs to such an output. We bound how many functions a single neuron can compute and extend this to a bound for a full network, giving our \emph{lower} bound on the neurons required. For the \emph{upper} bound, we give an explicit three-layer construction that can represent any target boolean function. Together, these bounds show that the number of neurons required for universal approximation grows exponentially in the input size: for $n$ input sequences with length $T_{in}$ and $T_{comp}$ computation time steps, the minimal required non-input neurons $R$ is bounded by: $R \in \Omega \bigg[\min\big(\frac{2^{nT_{in}}}{T_{comp}n^2}, \frac{2^{nT_{in}/3}}{\sqrt[3]{T_{comp}}}\big)\bigg]$ and $R \in O(2^{nT_{in}})$. 