
# Mitigating Catastrophic Forgetting in Spiking Neural Networks through Threshold Modulation

**Authors:** Ilyass Hammouamri

**Presentation type:** Poster

## Abstract

Artificial Neural Networks (ANNs) trained with Backpropagation and Stochastic Gradient Descent (SGD) suffer from the problem of Catastrophic Forgetting; when learning tasks sequentially, the ANN tends to abruptly forget previous knowledge upon being trained on a new task. On the other hand, biological neural networks do not suffer from this problem. Spiking Neural Networks (SNNs) are a class of Neural Networks that are closer to biological networks than ANNs and their intrinsic properties inspired from biology could alleviate the problem of Catastrophic Forgetting. In this paper, we investigate if the firing threshold mechanism of SNNs can be used to gate the activity of the network in order to reduce catastrophic forgetting. To this end, we evolve a Neuromodulatory Network that adapts the thresholds of an SNN depending on the spiking activity of the previous layer. Our experiments on different datasets show that the neurmodulated SNN can mitigate forgetting significantly with respect to a fixed threshold SNN. We also show that the evolved Neuromodulatory Network can generalize to multiple new scenarios and analyze its behavior.