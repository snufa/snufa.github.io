# Causal pieces: analysing and improving spiking neural networks piece by piece

**Authors:** Dominik Dold, Philipp Petersen
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

We introduce a novel concept for spiking neural networks (SNNs) derived from the idea of linear pieces used to analyse the expressivity and trainability of artificial neural networks (ANNs). We show that the input and parameter space of an SNN decomposes into distinct regions — which we call causal pieces — where the output spikes are caused by the same subnetwork. For integrate-and-fire neurons with exponential synapses, we prove that, within each causal piece, output spike times are locally Lipschitz continuous with respect to the input spike times and network parameters. Furthermore, we prove that the number of causal pieces is a measure of the approximation capabilities of SNNs. In particular, we demonstrate in simulation that parameter initialisations which yield a high number of causal pieces on the training set strongly correlate with SNN training success. Moreover, we find that SNNs with purely positive weights exhibit a surprisingly high number of causal pieces, allowing them to achieve competitive performance on benchmark tasks. We believe that causal pieces are a powerful and principled tool for improving SNNs, and may also provide new ways of comparing SNNs and ANNs in the future.