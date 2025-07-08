# Event-Based Learning of Synaptic Delays in Spiking Neural Networks with Exact Gradients

**Authors:** Balázs Mészáros, James Knight, Thomas Nowotny
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Spiking Neural Networks (SNNs) are gaining attention as energy-efficient alternatives to traditional rate-based neural networks, particularly for deployment on neuromorphic hardware. A key advantage of SNNs lies in their ability to incorporate temporal dynamics, characterised by synaptic and membrane time constants, as well as axonal, dendritic, and synaptic delays. In this work, we extend the EventProp[1] algorithm to include heterogeneous synaptic delays. We further derive the gradients for these delays, introducing a continuous time delay learning method. Notably, EventProp remains efficient by only requiring the storage of state variables at event (i.e., spike) times, even when introducing delays and/or learning them. This allows us to overcome memory bottlenecks faced by surrogate gradient methods that require storing state variables at every timestep. Furthermore, in contrast to the DelGrad[2] algorithm—another exact gradient-based method for delay learning in SNNs—our formalism allows for multiple spikes, making it suitable for a much wider class of applications. As far as we know, this is also the first gradient-based delay learning method to support recurrent connections. We validate our approach through our efficient GPU implementations, on standard benchmark simulations and the Yin-Yang[3] dataset, showing that our algorithm optimises delays from suboptimal initial conditions. Furthermore, we train on the Spiking Heidelberg Digits[4] dataset, leading to SOTA results with fewer parameters than prior work[5].

[1] Wunderlich,  Pehle. 2021. Scientific Reports 
[2] Göltz, et al. 2024. arXiv 
[3] Kriener, et al. 2022. Proc. Neuro-Inspired Conf. 
[4] Cramer, et al. 2020. IEEE
[5] Nowotny, et al. 2022. arXiv