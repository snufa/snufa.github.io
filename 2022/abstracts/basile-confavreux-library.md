
# Library of dynamics: linking parameters and behaviour of spiking networks with Simulation-Based Inference

**Authors:** Basile Confavreux*, Aaradhya Vaze*, Poornima Ramesh, Pedro Gonçalves, Jakob H. Macke and Tim P. Vogels

**Presentation type:** Poster

## Abstract

Since their inception over a century ago, various spiking neuron models have been proposed. Although we have a good understanding of how their parameters affect the behaviour of single neurons, a similarly complete intuition for how they affect the dynamics of connected groups of neurons is still lacking. Recent analytical work has provided a first glimpse of how a given model component can shape specific aspects of the resulting network dynamics (Sanzeni et al. 2022), but effects due to finite network size or irregular firing are difficult to predict analytically, and small changes in parameter settings can lead to large and unanticipated consequences. To understand how the variables of a neural network can act synergistically or antagonistically, we propose to assemble a library of network dynamics, i.e., a catalogue that links the influence of all important model parameters with various features of network dynamics.

To this end, we collect spike-trains from a wide range of models with various neuron and network parameters (such as network size, sparsity, connectivity and time constants). To obtain a function that connects network dynamics back to the underlying model parameters generating them, we use Simulation-Based Inference (SBI, Cranmer et al., 2020). This approach allows us to quantify network dynamics with metrics that can be defined post-hoc, without having to be analytically tractable. What’s more, the approach does not depend on the specifics of the network models and can be applied to networks of different single-neuron models -–ranging from leaky integrate-and-fire to adaptive exponential integrate-and-fire-– and a vast collection of network metrics.

Our library will complement the current analytical understanding of network models, and allow us to investigate properties such as model degeneracy, robustness and sensitivity to initialisation, providing qualitative and quantitative insight into if and why each model component is necessary for network behaviour.