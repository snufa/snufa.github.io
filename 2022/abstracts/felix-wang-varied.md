
# Varied Delays in Spiking Neural Networks Support Learning With Conjunctive Temporal Features

**Authors:** Felix Wang, Corinne Teeter

**Presentation type:** Poster

## Abstract

The learning paradigms between biological spiking neural networks compared to their artificial neural network counterparts are strikingly different, most notably in the use of local learning rules such as spike-time-dependent plasticity (STDP) as compared to global error backpropagation. There are also architectural differences such as the use of neural populations with relatively sparse connectivity as compared to neural layers with relatively dense connectivity. In this work, we highlight a less explored architectural difference: the use of varied connection delays between individual neurons. Due to their sensitivity to the timing between the spikes of the pre-synaptic and post-synaptic neurons, delays are one of the factors that influence STDP learning at a network level. Computationally, varied delays result in identical spiking patterns from upstream neurons being evaluated differentially in downstream neurons. We propose that this source of variability yields computational advantages in learning, especially with respect to temporally encoded inputs, as it confers the network access to a richer set of conjunctive temporal features. 

Toward this end, we have extended a recently developed method, EventProp [1], which derives an exact gradient across event-based neuron models, to compute its gradients through these varied delays. We implement this as an additional matrix specifying the connection delays between neurons, which we then use to construct indexical matrices to enable the proper alignment of spiking activity through the forward and backward passes of EventProp. Experimentally, we train against a simple, temporally encoded classification task using the Yin-Yang dataset, which was developed for research on biologically plausible error backpropagation. We found that incorporating varied delays to the network structure for this task resulted in improvements to training such as faster learning and increased robustness to hyperparameter tuning. We offer varied delays as a useful structural detail, and which also brings us closer to combining the different learning paradigms.

1	Wunderlich, T. C. & Pehle, C. Event-based backpropagation can compute exact gradients for spiking neural networks. Scientific Reports 11, 12829, doi:10.1038/s41598-021-91786-z (2021).

### Funding

Sandia National Laboratories is a multimission laboratory managed and operated by National Technology & Engineering Solutions of Sandia, LLC, a wholly owned subsidiary of Honeywell International Inc., for the U.S. Department of Energy’s National Nuclear Security Administration under contract DE-NA0003525.
