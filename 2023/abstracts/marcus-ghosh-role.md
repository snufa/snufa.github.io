# On the role of heterogeneity in multimodal networks 

**Authors:** Marcus Ghosh, Gabriel Béna, Volker Bormuth, Dan F. M. Goodman  

**Presentation type:** Poster at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

We continuously detect information via multiple sensory channels, like vision and hearing, and integrate these signals to realise faster and more accurate decisions. In biological networks, this process is implemented by multimodal neurons, which exhibit sub- to super-additive responses to multimodal stimuli; i.e., output fewer or more spikes than expected based on their unimodal responses. This heterogeneity could suggest that different multimodal neurons play distinct computational roles, like specialising on different tasks, however this hypothesis remains unaddressed experimentally.  

Here, we explore this idea through three computational experiments. First, by simulating single multimodal units, and using a firing rate approximation, we show that these heterogenous responses result from simple unit properties, like their membrane time constant and mean input firing rate. Second, by training spiking neural networks (SNNs) on four experimentally inspired multimodal tasks, via surrogate gradient descent, we demonstrate that training on different tasks generates multimodal units with differing responses. Finally, by performing ablations in our trained SNNs we demonstrate that sub-/super-additive units act as accumulators/coincidence-detectors, and so naturally specialise on different tasks.  

Ultimately, our work suggests that multimodal neurons with different properties may play distinct computational roles and demonstrates how task optimised SNNs can bridge the gap between experimental and computational work.  