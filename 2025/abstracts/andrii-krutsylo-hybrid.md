# Hybrid Spiking–Kolmogorov–Arnold Networks

**Authors:** Andrii Krutsylo
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

We present two hybrid architectures combining spiking neural networks (SNNs) with Kolmogorov–Arnold network (KAN) components to enhance temporal classification tasks. KANs are integrated in two configurations: the KAN-Readout SNN, which replaces the standard linear classifier with a spline-based readout; and the KAN-Integrated SNN, which inserts spline transforms inside each spiking layer. All models use leaky integrate-and-fire neurons.
Tasks are divided into static, sequential, and permuted settings. Static tasks use Poisson rate coding over T = 20 timesteps; sequential and permuted tasks are patch-based, using a single timestep per patch and Bernoulli spike encoding. Inputs are normalized prior to the spiking layers. Dense models (MLP, TKAN) use averaged rate inputs, while SNN variants process temporal sequences. Computational cost is measured as the sum of dense multiply–accumulate operations, event-driven synaptic operations, and spline element evaluations per sample.
On static FashionMNIST, MLP and TKAN achieve ~88.3% accuracy with ~0.305M operations/sample, while the baseline SNN reaches 88.32% at 7.75M operations. The KAN-Readout SNN matches this accuracy within −0.96% at similar cost, and the KAN-Integrated SNN achieves −4.25% accuracy at 49% lower compute.
On sequential FashionMNIST, the KAN-Readout SNN improves accuracy by +1.63% over the SNN baseline (67.98% vs. 66.35%) without extra compute, while the KAN-Integrated variant reduces compute by 47.6% with a −6.31% accuracy trade-off. In permuted tasks, the Readout model shows a +2.06% gain (61.76% vs. 59.70%), and the Integrated model again reduces compute by 47.6% with −4.71% in accuracy.
Results on MNIST follow the same trend.
These findings demonstrate that KAN-Readout SNNs can consistently boost accuracy on temporally structured tasks without increasing computational load, while KAN-Integrated SNNs offer significant efficiency gains with acceptable accuracy trade-offs. These trade-offs are reflected in lower inference times and memory usage, making the integrated design attractive for low-latency, resource-constrained neuromorphic systems.