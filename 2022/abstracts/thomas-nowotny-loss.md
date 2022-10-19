
# Loss matters: Limitations of learning with exact gradients in SNNs

**Authors:** Thomas Nowotny, James P. Turner, James C. Knight

**Presentation type:** Poster

## Abstract

In a recent paper (Event-based backpropagation can compute exact gradients for
spiking neural networks. Scientific Reports, 11(1):12829, 2021) Wunderlich and Pehle introduced the EventProp algorithm that allows learning by gradient descent on exact gradients in spiking neural networks. Here, we will discuss extensions of EventProp to a wider class of loss functions and an implementation in the GPU enhanced neuronal networks (GeNN) framework. The GPU acceleration allows us to test EventProp extensively on a number of increasingly challenging learning benchmarks. We find that EventProp performs well on some tasks but for others there are issues where learning is slow or fails entirely. 
We have analysed these issues in detail and discovered that they relate to the nature of the exact gradient of the employed loss functions. In particular, the exact gradient does not provide information about loss changes due to changes in weights that lead to additional spikes or the removal of spikes. It only carries information related to changes in spike times. Depending on the details of the task and the loss function, descending the exact gradient with EventProp can, therefore, lead to the deletion of important spikes and so to an inadvertent increase of the loss and decrease of classification accuracy. This can lead to a failure to learn. 
In other situations the lack of knowledge about the benefits of creating additional spikes can lead to a lack of gradient flow into earlier layers, slowing down learning.