# Training fast spiking networks through STDP and control feedback

**Authors:** Alexander Efremov, Martino Sorbaro, Pau Vilimelis Aceituno, Benjamin Grewe

**Presentation type:** Short talk at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

It is not currently known how the brain sidesteps the need for error backpropagation in training multi-layered hierarchical networks. Hebbian plasticity rules such as Spike Timing-Dependent Plasticity (STDP) play a key role in learning in biological networks, but are, by themselves, unsupervised learning, and it is not clear how they could incorporate error signals in a supervised setting.

Our recent work (e.g. Aceituno et al. 2023) suggests that a controller can provide a valid feedback error signal to be used in combination with temporal Hebbian rules in deep neural networks. However, previous work is limited to continuous, rate-based networks, and to stationary inputs. In contrast, biological spiking networks are known to be extremely fast in inference, classifying inputs even with a single spike per neuron. Rate-based models cannot faithfully represent this coding strategy, its low latency, nor its energy efficiency.

In this project, we combine STDP with a controller-driven learning signal to train multi-layer, hierarchical, spiking networks that are both fast (low-latency) and correct (low-error). The method does not need changes to the STDP rule such as third factors, and is suited to neuromorphic implementations. We verify it on standard benchmarks, with results close to those given by backpropagation. The algorithm also works in “feedback alignment” mode, i.e. without the need to train the backward weights.

We show that this training strategy indeed leads to low-latency networks that can naturally implement first-spike coding in the output layer. This temporal encoding emerges naturally from training, even though the network training begins in a regime where many spikes are produced. This is compatible with experimental observations in the brain’s cortex, where new stimuli that are yet to be learned elicit slower responses, while inference on familiar stimuli is fast (Nayebi et al.) and limited to a few spikes (Delorme & Thorpe).

[Watch it on Youtube](https://youtu.be/SZsATr3-b0I?si=t1FiD5TTBDMr39Ro)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/SZsATr3-b0I?si=t1FiD5TTBDMr39Ro" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>