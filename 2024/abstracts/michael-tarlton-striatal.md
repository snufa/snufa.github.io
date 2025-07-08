# Striatal Beat Frequency RL Automata as a Model of Time Cell Attenuation

**Authors:** Michael Tarlton
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Deep Learning is limited by the current method of credit-assignment, Back-Propagation (BP), which is impossible to utilize in deep non-linear architectures as found in the brain. BP is also difficult to implement in Spiking Neural Networks (SNNs), which offer a tremendous number of advantages over current network models. If we are going to take full advantage advantage of SNNs we must apply better methods of credit-assignment such as found in the brain.

As spiking communication is inherently time-based, we may be able to adapt known models of temporal dynamics and learning in the Brain for new methods of credit-assignment for SNNs. Time may add a dimension for triangulating credit-assignments to neurons in deep and otherwise unnavigable systems.

We study the smallest receptive field of timing on the Brain, the ability to distinguish and internally represent a single interval of time at the minimal scale: in the sub 100ms range. The difficulty lies, in constructing a neural model which can r learn and represent an interval of time in the sub-to-suprasecond range, from neurons with firing rates in the range of tens-of-milliseconds. I.e. How can time dynamics of one scale emerge into time dynamics at higher scales?

The Striatal Beat Frequency (SBF) is a neuroanatomical model of interval timing in the brain which encodes representation a target time-interval on the distribution of weights in circuit of spike-firing neurons. The design of the SBF allow for flexibility and scalability in online learning environments with neuromodulatory input.

We adapt the SBF model in a naïve neural automata which learns in an RL interval timing task and show its performance in a “single neuron” network for a variety of conditions and tasks.