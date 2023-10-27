# How do receptor secretion and transport properties lead to the regularization of synaptic plasticity and benefit learning?

**Authors:** Oleg Nikitin, Olga Lukyanova, Alex Kunin

**Presentation type:** Flash talk at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

It is common to simulate synaptic plasticity as a process resembling the dynamics of biological neural cells and governed by mathematical equations. In most cases, those equations reproduce the overall observed dynamics. However, such equations often lack control of the limitations for instantaneous rate of change (derivation) and any proactive dynamics of the derivation of synaptic plasticity.

However, in biological neurons, the physical limitations define plasticity. Change in the synaptic strength depends on the concentration of membrane receptor proteins. These proteins are secreted and transported by the adaptive systems inside the neural cell, located in the nucleus, endoplasmic reticulum, and Golgi apparatus, and governed by Genetic regulatory networks (GRN) and Protein–protein interaction (PPI) networks.

We examine how the innate features of cellular dynamics govern and regularize the synaptic weight dynamics and reproduce the dynamics as a system of equations optimizing the pattern recognition in spiking neural networks. Computational mechanisms like reservoir computing reproduce GRNs and PPIs and regulate the neural activity toward the desired firing rate or maximize the signal discrimination. Such a system achieves heterosynaptic plasticity simultaneously, keeping the homeostasis and excelling over other approaches, such as homeostatic scaling.

We introduce novel mechanics of interconnection between neuron firing rate homeostasis and weight change through STDP growth bounded by abstract protein reserve controlled by the intracellular optimization algorithm. Plasticity dynamics restricted by receptor pool help neurons filter out noise signals while keeping a stable firing rate. Nevertheless, such filtering does not affect the ability of neurons to recognize the correlated signals. 

We would like to discuss the role of physical limitations in neural systems and how such limitations define and assist intelligent behavior and might be used in the machine learning domain to improve the robustness of AI systems.