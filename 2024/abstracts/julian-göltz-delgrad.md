# DelGrad: Exact gradients in spiking networks for learning transmission delays and weights

**Authors:** Julian Göltz, Jimmy Weber, Laura Kriener, Sebastian Billaudelle, Peter Lake, Melika Payvand, Mihai A. Petrovici
                           
**Presenting author:** Julian Göltz and Jimmy Weber

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Spiking neural networks (SNNs) inherently rely on the timing of signals for representing and processing information. Recent work [1, 2] has demonstrated substantial advantages of learning transmission delays along with synaptic weights, both in terms of accuracy and memory efficiency. However, these approaches suffer from drawbacks in terms of precision and learning efficiency, as they operate in discrete time and with approximate gradients, while also requiring membrane potential recordings for calculating parameter updates.

To alleviate these issues, building on prior work on exact gradients in SNNs [3] we propose an analytical approach for calculating exact gradients of the loss with respect to both synaptic weights and delays in an event-based fashion. The inclusion of delays emerges naturally within our proposed formalism, enriching the model's parameter search space with a temporal dimension. Our algorithm is purely based on the timing of individual spikes and does not require access to other variables such as membrane potentials.

We explicitly compare the impact on accuracy and parameter efficiency of different types of delays - axonal, dendritic and synaptic - in the Yin-Yang classification task [4]. Furthermore, while previous work on learnable delays in SNNs has been mostly confined to software simulations, we demonstrate the functionality and benefits of our approach on the BrainScaleS-2 neuromorphic platform [5]: in a proof-of-concept study we implement transmission delays by repurposing neuron circuits as delay elements and show desirable configurability and reproducibility. Additionally, we train a network containing these delay elements with an in-the-loop training approach and demonstrate their advantages compared to weight-only optimization.

DelGrad presents an event-based framework for gradient-based co-training of delay parameters and weights, without any approximations, and which meets the typical demands and constraints of neuromorphic hardware, as demonstrated experimentally by successfully training on an analog mixed-signal neuromorphic system.

[1] Shrestha, S. B. & Orchard, G. SLAYER: Spike Layer Error Reassignment in Time
[2] Hammouamri, I., Khalfaoui-Hassani, I. & Masquelier, T. Learning Delays in Spiking Neural Networks using Dilated Convolutions with Learnable Spacings, 10.48550/arXiv.2306.17670
[3] Göltz, J., Kriener, L., et al. Fast and energy-efficient neuromorphic deep learning with first-spike times., 10.1038/s42256-021-00388-x
[4] Kriener, L., Göltz, J. & Petrovici, M. A. The Yin-Yang Dataset, 10.1145/3517343.3517380
[5] Pehle, C., Billaudelle, S., et al. The BrainScaleS-2 Accelerated Neuromorphic System with Hybrid Plasticity., 10.3389/fnins.2022.795876
