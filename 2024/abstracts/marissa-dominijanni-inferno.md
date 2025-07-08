# Inferno: An Extensible Framework for Spiking Neural Networks

**Authors:** Marissa Dominijanni
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

This paper introduces [library name], a software library built on top of PyTorch that is designed to meet distinctive challenges of using spiking neural networks (SNNs) for machine learning tasks. We describe the architecture of [library name] and key differentiators that make it uniquely well-suited to these tasks. We show how [library name] supports trainable heterogeneous delays on both CPUs and GPUs, utilizing gather operations to exploit the inherent parallelism of the latter. We describe features of [library name] that enable a “write once, apply everywhere” development methodology for novel models and techniques. Key among these are generalized reshaping operations on tensors of presynaptic and postsynaptic spikes to turn the connection-dependent comparisons for pre-post learning rules like spike-timing dependent plasticity (STDP) into a single Einstein summation. Among several examples, we show how the design decisions made by [library name] facilitate easily implementing the new methods of Nadafian and Ganjtabesh in delay learning with STDP.

Finally, we compare [library name]'s performance to BindsNET, a library aimed at machine learning with SNNs, and Brian2/Brian2CUDA which is popular in neuroscience. For this, we set up benchmarks that simulate generating a homogenous Poisson spike train, a group of leaky integrate-and-fire neurons, and a dense linear connection between them; with or without updating the weights using STDP. On these benchmarks, [library name] demonstrated comparable performance to BindsNET and Brian2/Brian2CUDA.