# On the role of temporal hierarchy in Spiking Neural Networks

**Authors:** Filippo Moro, ‪Pau Vilimelis Aceituno‬, Laura Kriener, Melika Payvand
                           
**Presenting author:** Filippo Moro

**Presentation type:** Talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Spiking neural networks (SNN) are endowed with inherent temporal computational elements, such as neuronal dynamics and transmission delays. Such temporal features allow SNNs to perform temporal tasks (Indiveri et al. 2019). However, the inductive biases and best practices to effectively set such parameters remain an open question.
Here we address this problem by focusing on multi-layer SNNs, where the network follows a hierarchical structure. Following insights from neuroscience (Murray et al. 2014) we argue that hierarchical SNNs should have a temporal hierarchy to match their structure: the layers closer to the input should have fast temporal dynamics while late layers closer to the output should have slow temporal dynamics.
We show the advantages of the temporal hierarchy by setting them as an inductive bias. We consider deep feedforward SNNs with leaky integrate and fire neurons and use them to solve temporal tasks (Multi-Time-Scale XOR and Keyword Spotting), leading to an increase of 4% in classification accuracy. Furthermore, we show that a similar hierarchy of time constants emerges when optimizing the time constants through gradient descent. We complement these results with mathematical derivations where we leverage the uncertainty principle of signal processing to prove that early layers must have short time constants that can capture high frequencies. In contrast, later layers must have long time constants that can accumulate information over long times.
Finally, our results generalize to SNN with different temporal parameters. We use temporal convolutions, where the size and dilation of temporal kernels are set as initial biases, leading to significant performance improvements. We also train hierarchical recurrent SNNs and analyze the dynamics of each recurrent layer after training, which also shows slower dynamics on the later layers.