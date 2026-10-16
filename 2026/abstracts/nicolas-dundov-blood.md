# Blood and Modularity: A Brain-Inspired Approach to Functional Disentangled Neural Representations

**Authors:** Nicolas Dundov, Dan Goodman
                           
**Presenting author:** Nicolas Dundov

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Intelligent systems in real environments must process multi-modal stimuli in real time. At the
neural network level, this requires coordinating complex interactions across an expansive state
space. Given the combinatorial explosion in the number of potentially relevant interactions
between inputs, it quickly becomes intractable to compute every possibility. Given the brain is
a resource-constrained system, it must have evolved efficient mechanisms for dealing with this
problem. A trait of particular interest is modularity: The emergence of separable representations
within the network from distinct or entangled inputs. Purely functional modularity allows a
system to break down complex functions into separable sub-functions across the state space
without having to compute every representation, resulting in an energy efficient network with
fewer and more focused activations. It may also facilitate transfer learning across solutions that
generalise beyond the training distribution.
We developed a novel network architecture featuring an energy allocator inspired by blood
distribution mechanisms in the brain during periods of intense focus (fig 1a). In our model, the
allocator network, which is jointly trained with the primary network, decides how much energy
each spatial region should receive (with a fixed total budget). The less energy a region has, the
noisier its outputs. This encourages the network to align spatial regions with functional
modules. We evaluated this model on a paired KMNIST/MNIST modular classification task.
To understand what influences the emergence of modularity in a multi-layer perceptron (MLP),
we conducted a parameter grid search (fig 1b). Changing the total energy available for
distribution had a significant effect, where excess energy led to an exponential decay in
modularity, suggesting limited resource allocation enhances emergence.
The network successfully achieves functional modularity and high classification accuracy
across a fully connected MLP architecture, isolating distinct representations without structural
partitioning.
This could both provide a scalable framework to encourage the emergence of functional
modularity in Artificial Neural Networks and potentially explain its emergence in the brain.
This blueprint could be translated into varied network configurations and sizes benefiting
specialised, energy efficient neuromorphic computing systems.