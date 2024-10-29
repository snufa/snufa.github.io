# Credit assignment through sampling in Poisson Spiking Neural Networks

**Authors:** Tifenn Hirtzlin
                           
**Presenting author:** Tifenn Hirtzlin

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Spiking Neural Networks (SNNs) are a promising computational paradigm for the future of circuit design implementation, leveraging the timing of neuron spikes for information processing. Despite their potential, their application has been limited due to challenges in credit assignment and error backpropagation, which are essential for training deep neural networks. This paper introduces a novel method for credit assignment in Poisson spiking neural networks through probabilistic sampling techniques, specifically leveraging the properties of Poisson processes.
Traditional approaches to SNN training face difficulties because spikes are inherently non-differentiable. Current state-of-the-art techniques use surrogate gradients to approximate the derivatives needed for backpropagation. However, this method often require extensive temporal simulations and are not hardware-compatible.
Our proposed solution addresses these limitations by utilizing probabilistic methods to compute error derivatives. By modeling spike trains as Poisson random processes, we can estimate the gradients through sampling. This approach allows us to derive an efficient learning rule that approximates backpropagation in a biologically plausible manner. 
Moreover, this method supports broader applicability across various types of neuron activation sampling, although it typically requires a large number of samples due to the sparse activity of neurons. The Bayesian nature of this sampling process aligns well with the observed neural coding strategies in the brain, offering a more biologically realistic framework for SNN training.
Our work presents a robust framework for error derivative calculation using probabilistic sampling in Poisson spiking neurons. Future work will focus on developing neuromorphic circuits for on-chip learning using probabilistic approaches. This advancement paves the way for more efficient and biologically inspired neural network training methodologies.
