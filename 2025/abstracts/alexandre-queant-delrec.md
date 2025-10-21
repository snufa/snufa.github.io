# DelRec: learning delays in recurrent spiking neural networks.

**Authors:** Alexandre Queant, Ulysse Rançon, Benoit R Cotterau, Timothée Masquelier
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

In Spiking Neural Networks (SNNs), each synapse is characterized not only by a weight but also by a transmission delay. While theoretical works have long suggested that trainable delays significantly enhance expressivity, practical methods for learning them have only recently emerged. To date, only a handful of studies have explored the potential of delays in recurrent connections, and even fewer have focused on learning optimal delay configurations. Here, we introduce "DelRec'', the first SGL-based method to train axonal or synaptic delays in recurrent spiking layers, compatible with any spiking neuron model. DelRec leverages a differentiable interpolation technique to handle non-integer delays with well-defined gradients at training time. We show that trainable recurrent delays outperform feedforward ones, leading to new state-of-the-art (SOTA) on two challenging temporal datasets (Spiking Speech Command, an audio dataset, and Permuted Sequential MNIST, a vision one), and match the SOTA on the now saturated Spiking Heidelberg Digit dataset using only vanilla Leaky-Integrate-and-Fire neurons with stateless (instantaneous) synapses. Our results demonstrate that recurrent delays are critical for temporal processing in SNNs and can be effectively optimized with DelRec, paving the way for efficient deployment on neuromorphic hardware with programmable delays. Our code is available at https://anonymous.4open.science/r/Recdel-4175.