# Exploring the Potential of Heterogeneous Spiking Neural Networks for Neuro-AI Advancements

**Authors:** Biswadeep Chakraborty

**Presentation type:** Short talk

## Abstract

The emergence of computing technologies based on the brain is offering innovative energy-efficient information processing methods. Spiking Neural Networks, regarded as the third wave of Artificial Intelligence, are based on the learning principles in the brain, making them a biologically plausible model of neural processing.

We present our work on a heterogeneous recurrent spiking neural network, which consists of heterogeneous neurons with varying firing/relaxation dynamics. The model learns using a heterogeneous STDP model with varying learning dynamics for each synapse. 
Our analytical investigations and empirical results reveal that the heterogeneity in the integration and relaxation dynamics of neurons significantly enhances the HRSNN's ability to learn distinct input patterns, resulting in a higher memory capacity. This, in turn, leads to improved performance of the model. Furthermore, we demonstrate that the heterogeneous dynamics of synapses, as governed by STDP, reduce spiking activity while preserving memory capacity.

We show that heterogeneity in neuronal dynamics increases memory capacity by capturing more principal components from the input space, leading to better performance and improved memory capacity. Furthermore, heterogeneity in the STDP dynamics decreases spike activation, providing better orthogonalization among the recurrent network states and a more efficient representation of the input space, lowering higher-order correlation in spike trains. Finally, incorporating heterogeneity in both neuron and STDP dynamics enhances the model performance while reducing spike counts.

The applicability of the HRSNN model extends to spatio-temporal classification tasks, including video activity recognition. Our experiments yield impressive accuracy scores, with 94.32% accuracy achieved on the KTH dataset, 79.58% and 77.53% on the UCF11 and UCF101 datasets, respectively, and a remarkable 96.54% accuracy on the event-based DVS Gesture dataset using our novel unsupervised HRSNN model. 

In conclusion, the integration of heterogeneity in neuronal and synaptic dynamics not only reduces the spiking activity of Recurrent Spiking Neural Networks but also enhances their prediction performance, ushering in an era of spike-efficient learning. This research contributes to the broader exploration of NeuroAI and its potential to bridge the gap between artificial systems and the complexities of biological intelligence.