# Surrogate Surrogate Gradients

**Authors:** Chen LI
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Human intelligence is driven by the intricate dynamics of spiking neurons in the brain, inspiring the development of spiking neural networks (SNNs) as a biologically-plausible model for artificial intelligence. Despite their promise, training SNNs to approximate complex functions remains challenging due to inefficiencies in current methods, which require significant memory and often compromise accuracy. Here, we introduce a novel approach that simplifies SNN training by folding time into the network and leveraging a temporal gradient estimator for more efficient backpropagation. This strategy reduces the training complexity from O(T) to O(1), significantly cutting both computational costs and memory usage. Our method also supports the simulation of refractory periods during both the training and inference phases. Additionally, we propose a new loss function designed to prompt SNNs to produce faster responses during inference. The SNNs trained with our method achieve state-of-the-art results on the CIFAR-10 dataset and deliver competitive performance on ImageNet, outperforming other memory-efficient surrogate gradient methods and being on par with leading surrogate gradient techniques.