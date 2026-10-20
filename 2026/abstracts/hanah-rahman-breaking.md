# Breaking Point, Engineered: Agents That Design, Prove, and Certify Fault-Tolerant Spiking Networks

**Authors:** Hanah Rahman
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Spiking neural networks (SNNs) operate on neuromorphic hardware. The neurons within these SNNs may cease to operate over time due to the loss of the electrical signals that they produce. However, the robustness of an SNN is still measured via a manual test on each individual SNN. Yet, there is no theory that describes when the trained SNN may fail.

This work unifies the science of that collapse with the engineering procedures necessary for the certification of the SNN.

Science. The rate of failure of the SNN (p) can be controlled through a variety of parameters of the SNN itself. Each unit within the SNN is redundant to maintain its function despite the potential loss of some of its neurons. The use of coding strategies within the SNN to protect the signals that are emitted by its neurons, alongside techniques from non-Hermitian physics can lead to the maintenance of the function of the SNN despite the failure of its neurons. The rate of failure of the SNN can also be forecasted using the information of the SNN itself. Lastly, through the use of machine checked theorems, the SNN may be built with less than log(M/δ) neurons for each unit of the SNN.

Engineering. The science of the SNNs can be implemented and tested with a variety of artificial intelligence models. The development of the SNNs can be managed with six artificial intelligence agents with specific roles in the development and testing of the SNNs. These agents are managed by the artificial intelligence models of the system itself.

Experiment. Six variations of the SNNs (standard, with dropout, with the PT technique, with coding, with both PT and coding, and with homeostatic thresholds) are tested by both neuron failures and the loss of signals within the SNN. Six variations of the SNNs are produced to determine the increase in their failure rate, the impact of PT on their failure rate and coding of their signals, the failure rate of the SNN as determined by its neural parameters, and the potential benefit of using both PT and the theories behind their failures.

With the development of AI agents that engineer the fault tolerance of the SNNs, it is no longer necessary to manually test their robustness. Instead, their fault tolerance is verified through the various agents and tests prior to their fabrication.