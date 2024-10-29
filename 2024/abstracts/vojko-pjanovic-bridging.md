# Bridging sampling methods with attractor dynamics in spiking models of head direction systems

**Authors:** Vojko Pjanovic, Jacob Zavatone-Veth, Ann Hermundstad, Paul Masset, Sander Keemink, Michele Nardin
                           


**Presentation type:** Flash talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Uncertainty is a fundamental aspect of the natural environment. To deal with this uncertainty, the brain may employ sampling-based methods. Many previous studies considered sampling-based inference, with major examples arising from the encoding and decoding of visual stimuli, but sampling-based methods could also be employed in higher-order brain areas. The head-direction system is a prominent example of this, where noisily encoded angular velocity estimates need to be inferred and integrated into a circular attractor to keep track of the heading direction. 

Here, we derive a spiking neural network with local nonlinearities that performs sampling-based inference and integration of noisily encoded inputs on a manifold, based on the theory of spike coding networks. To this end, we extend the sampling capabilities of spike coding networks — previously constrained to sampling from Gaussian distributions — to the exponential family distributions. We describe the precise requirements at the network, cellular, and synaptic levels for sampling from distributions with different moment functions, and implement sampling-based inference of latent stimuli encoded by noisy Poisson neurons. We then use this to develop a model for the head direction system, in which inferred angular velocities are integrated on a ring-shaped prior. The model bridges sampling-based inference dynamics with attractor dynamics, and we provide concrete, testable predictions about correlated subthreshold voltages, short- and long-term neural activity correlation patterns, and statistics of bump movement.

Our work showcases how sampling-based computations could be used in higher-order brain areas, paving the road for bridging probabilistic methods with attractor dynamics in spiking neural networks. Moreover, we offer an alternative perspective on the neural computations responsible for orientation and navigation, providing testable predictions about neural activity that can be examined in future neuroscientific experiments.
