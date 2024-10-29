# Using Dynamical Systems Theory to Improve Surrogate Gradient Learning in Spiking Neural Networks

**Authors:** Rainer Engelken, Larry Abbott
                           


**Presentation type:** Talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Spiking Neural Networks (SNNs) promise energy efficiency and offer a more brain-like alternative to artificial neural networks. A major challenge to unleashing their potential, however, making them trainable on tasks that require credit assignment across long time horizons. Gradient-based learning, which has driven much of the recent success in ANNs, is hampered in spiking networks by their discrete spiking interactions, which make the error landscape non-differentiable. A recent approach to this challenge is to replace the spike interaction with a surrogate gradient in the backward pass of gradient descent. Training spiking networks with surrogate gradients, however, can be prone to exploding and vanishing gradients especially for temporally complex tasks. 

Here, we tackle the challenge of temporal credit assignment in spiking networks using concepts from dynamical systems theory. We leverage a link between the error gradient and Lyapunov exponents of the network dynamics to mitigate exploding and vanishing gradients in spiking network training. 
We demonstrate that surrogate Lyapunov exponents (i.e. computed with the surrogate spike function), which quantify the exponential temporal growth rate of activity perturbation, predict error gradients in spiking networks for tasks that require bridging long time horizons.

We leverage differentiable linear algebra to regularize surrogate Lyapunov exponents in a method we call surrogate gradient flossing and show that this creates slow tangent modes that facilitate gradient signal propagation over time scales that exceed the intrinsic time scales of individual neurons. We then demonstrate that surrogate gradient flossing improves training speed and success rates on tasks with long time horizons. 

In summary, we use dynamical systems theory to better understand and mitigate exploding and vanishing gradients in spiking neural networks. Our insights and methods open an avenue for improved training protocols for brain-like models in theoretical neuroscience and neuromorphic computing and suggest collective mechanisms for neuronal temporal credit assignment.