# A Causal Perspective on Surrogate Gradient Learning in Spiking Neural Networks

**Authors:** James Walker, Moein Khajehnejad, Adeel Razi
                           


**Presentation type:** Flash talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

The surrogate gradient method has emerged as a pivotal technique for training Spiking Neural Networks (SNNs), effectively addressing the challenge of non-differentiable spiking activations by replacing them with smooth approximations. Despite its empirical success and state-of-the-art performance, its theoretical foundations remain relatively underexplored.

In this work, we reframe learning in SNNs as a causal inference problem, interpreting gradient computation as estimating the causal effect of network parameters on the loss function. By applying causal inference techniques, including instrumental variables and the backdoor criterion, we demonstrate parallels between these methods and established gradient estimation approaches, such as the REINFORCE algorithm.

We next investigate how the causal effect of any given neuron on the loss can be informed by the causal effect of connected downstream neurons on the loss, using causal inference techniques akin to the front-door criterion. The existence of multiple causal pathways between neurons and the loss function introduces confounding issues, as interactions within the network can obscure the direct impact of individual neurons on the loss. We show that the natural solution to this issue is to introduce independent noise perturbations to neurons in the network, enabling the propagation of approximate unconfounded causal effects throughout the network. Importantly, applying a linear approximation to this technique results in a learning algorithm equivalent to the surrogate gradient method, providing a novel theoretical perspective on this method.

This causal inference perspective not only deepens our theoretical understanding of the surrogate gradient method but also offers practical guidance for selecting and designing surrogate functions. Our findings contribute to a stronger conceptual foundation for SNN training and open new avenues for more effective, causally informed learning strategies.
