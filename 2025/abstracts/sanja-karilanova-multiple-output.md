# Multiple-Output Spiking Neurons with Generalized Reset Feedback Mechanisms

**Authors:** Sanja Karilanova, Subhrakanti Dey, Ayça Özçelikkale
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking neural networks (SNNs) are biologically inspired neural networks which utilize statefull neurons and low-bit data processing using spikes. Another family of deep sequence models, called deep state-space models (SSMs), have recently achieved state-of-art performance in a large range of temporal modeling tasks. However, deep SSMs are typically designed with high-precision data processing and no reset mechanisms, differentiating them conceptually from SNNs. Leveraging the complementary strengths of SNNs and  deep SSMs, in this paper we propose a  multiple-output spiking neuron model that integrates a general linear SSM-style state transition with spike-based communication and a novel nonlinear reset-based feedback mechanism. In contrast to conventional spiking neuron formulations, our model explicitly separates the roles of the spiking function, the reset condition, and the reset action. Experiments across diverse tasks, including keyword spotting, event-based vision, and sequential pattern recognition,  demonstrate that the proposed approach reaches performance on par with established benchmarks in the SNN field. Furthermore, our findings highlight that the reset mechanism can counteract instability and support learning even when the linear dynamics of the neuron are unstable, thus extending beyond the strict stability requirements typically imposed in recent deep SSM designs.