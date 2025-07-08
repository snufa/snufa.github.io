# Storing overlapping associative memories on latent manifolds in low-rank spiking networks

**Authors:** William Podlaski, Christian Machens
                           


**Presentation type:** Talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Associative memory architectures such as the Hopfield network have long been important conceptual and theoretical models for neuroscience and artificial intelligence. However, translating these abstract models into spiking neural networks has been surprisingly difficult. Indeed, previous work has been restricted to storing a small number of primarily non-overlapping memories in large spiking networks, thereby limiting their scalability. Here, we revisit the associative memory problem in light of recent advances in understanding spike-based computation. Using a recently-established geometric framework , we show that spiking activity for a large class of all-inhibitory networks is situated on a low-dimensional, convex, and piecewise-linear manifold, with dynamics that move along the manifold. We then map the associative memory problem onto these dynamics, and demonstrate how the vertices of the manifold can be used to store many stable, overlapping activity patterns with a direct correspondence to the original Hopfield model. We propose several learning rules, and demonstrate a linear scaling of the storage capacity with the number of neurons, as well as robust pattern completion abilities. Overall, this work serves as a case study to demonstrate the effectiveness of using a geometrical perspective to design dynamics on neural manifolds, with implications both for neuroscience and machine learning.