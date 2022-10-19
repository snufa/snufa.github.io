
# Population geometry enables fast sampling in spiking neural networks

**Authors:** Paul Masset, Jacob A. Zavatone-Veth, J. Patrick Connor, Venkatesh N. Murthy and Cengiz Pehlevan

**Presentation type:** Poster

## Abstract

Neural circuits perform probabilistic computations at the sensory, motor and cognitive levels. To be behaviorally useful, these probabilistic computations must occur at the speed of perception. However, how neuronal dynamics allow brain circuits to represent uncertainty in high-dimensional spaces at perceptual timescales remains unknown. Sampling-based algorithms afford a theoretically-grounded framework for probabilistic inference but their implementation in biologically-plausible spiking networks remains an open question. Here, we propose to leverage the population geometry, controlled by the neural code and the neural dynamics, to implement fast samplers in spiking neural networks.

First, we construct from first principles a novel spiking neural network model for sampling from multivariate Gaussian distributions. This model is based on a probabilistic spike rule that implements approximate Metropolis-Hastings sampling. We show that efficient balanced networks emerge as a limit of this model in which spiking becomes deterministic. Next,  we show that a careful choice of population geometry, corresponding to the natural space of parameters, enables rapid inference of parameters drawn from strongly-correlated high-dimensional distributions. Leveraging the “complete recipe” for stochastic gradient Markov Chain Monte Carlo, we establish principles for the design of efficient samplers in spiking neural networks. We show how neural population geometry enables fast sampling---on the timescale of tens of milliseconds---in two limits of our model: efficient balanced networks in which sampling is driven by stochastic Langevin dynamics , and networks in which sampling is driven purely by a Metropolis-Hastings probabilistic spiking rule. 

Our results suggest design principles for algorithms for fast sampling-based probabilistic inference in spiking neural networks, yielding potential inspiration for neuromorphic computing and testable predictions for neurobiology.