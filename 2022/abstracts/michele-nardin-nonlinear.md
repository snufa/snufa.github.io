
# Nonlinear computations in spiking neural networks through multiplicative synapses

**Authors:** Michele Nardin, James W Phillips, William F Podlaski, Sander W Keemink

**Presentation type:** Talk

## Abstract

The brain efficiently performs nonlinear computations through its intricate networks of spiking neurons, but how this is done remains elusive. While recurrent spiking networks implementing linear computations can be directly derived and easily understood (e.g., in the spike coding network (SCN) framework), the connectivity required for nonlinear computations can be harder to interpret, as they require additional non-linearities (e.g., dendritic or synaptic) weighted through supervised training. Here we extend the SCN framework to directly implement any polynomial dynamical system. This results in networks requiring multiplicative synapses, which we term the multiplicative spike coding network (mSCN). We demonstrate how the required connectivity for several nonlinear dynamical systems can be directly derived and implemented in mSCNs, without training. We also show how to precisely carry out higher-order polynomials with coupled networks that use only pair-wise multiplicative synapses, and provide expected numbers of connections for each synapse type. Overall, our work provides an alternative method for implementing nonlinear computations in spiking neural networks, while keeping all the attractive features of standard SCNs such as robustness, irregular and sparse firing, and interpretable connectivity. Finally, we discuss the biological plausibility of mSCNs, and how the high accuracy and robustness of the approach may be of interest for neuromorphic computing.