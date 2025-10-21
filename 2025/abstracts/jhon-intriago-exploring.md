# Exploring Information-Constrained Latent Spaces in Adaptive Spiking Neural Networks

**Authors:** Jhon Intriago, Pablo A. Estévez
                           


**Presentation type:** Flash talk at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Adaptive Spiking Neural Networks (ASNNs) are highly efficient and biologically plausible, making them promising candidates for next-generation artificial intelligence. However, information constraints within their latent spaces often impede convergence and restrict overall performance. In this work, we tackle this challenge by introducing a novel method for optimizing latent space representations in ASNNs. This method is grounded in the principle of the information bottleneck, aiming to optimize the trade-off between compression and relevance in latent representations. Our approach improves convergence rates and training efficiency without compromising model accuracy.

The proposed method was evaluated in the Spiking Heidelberg Digits dataset with 700 dimensions and 0.01ms simulation time (100 sequence length). The proposed information-constrained ASNN achieved optimal performance in significantly fewer epochs compared to the unconstrained baseline. Specifically, our results show a statistically significant reduction in the number of epochs by an average of 4 with the constrained model, while still achieving a marginal overall performance improvement. This work highlights the critical role of leveraging information-constrained latent spaces to accelerate training, boost convergence, and improve the efficiency of ASNNs for real-time, large-scale applications.