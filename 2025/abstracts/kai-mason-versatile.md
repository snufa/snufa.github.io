# Versatile Learning in Neural Networks Without Synaptic Plasticity

**Authors:** Kai Mason, Sonia Sennik, Claudia Clopath, Aaron Gruber, and Wilten Nicola
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Learning and memory are often attributed primarily to synaptic weight change, yet growing in vivo and in silico evidence also implicates modulation of intrinsic excitability and/or gated subcortical inputs as important components of these processes. 

To test the ability of such inputs to influence network processing, we evaluated learning without synaptic plasticity in the Bias Adaptive Neural Firing Framework (BANFF), in which synaptic weights are fixed and each neuron learns a bias current.  We study two BANFF architectures with static ternary postsynaptic weights and an excitatory/inhibitory split: (i) a recurrent single-hidden-layer network comprising 6000 neurons and (ii) a feedforward network with two hidden layers comprising 16,000 neurons each. Biases were trained by supervised gradient descent .

 The recurrent BANFF successfully emulated 35 chaotic dynamical systems, reproducing target phase portraits. The feedforward BANFF solved 24 tasks across five categories: classification, regression, motor control, game play, and time series prediction and modelling. Performance was comparable to common benchmarks: classification 90 ± 11% (mean ± SD, N = 11), regression r = 0.87 ± 0.15 (N = 2), 99% success on a two-joint arm-reach task, 99% hit-rate in Pong against a perfect opponent. Training multiple tasks in a single network incurred no catastrophic forgetting. Learned bias distributions and firing-rate profiles exhibited task-specific excitability signatures.   

Bias-only learning thus achieves learning with trainable parameters scaling linearly with network size, robust multi-task capability, and interference-resistant retention, offering a parsimonious and biologically plausible alternative to synaptic plasticity. These results support the hypothesis that rapid cortical learning can arise from modulation of intrinsic excitability and/or subcortical bias currents. Preliminary work emulating these results in spiking neural networks with adaptive leaky integrate-and-fire (ALIF) neurons is underway with positive results in training the bias currents to spiking neurons so that they can perform dynamical system mimicry, classification and regression tasks.

