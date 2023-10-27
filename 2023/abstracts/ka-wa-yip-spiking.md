# Spiking neural networks as universal quantum simulators

**Authors:** Ka-Wa Yip

**Presentation type:**  at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

Simulating quantum dynamics using current digital CMOS hardware remains challenging. We often rely on approximations like Hamiltonian truncations and focus primarily on the dynamics of low-lying eigenstates. The biological brain has not been rigorously defined within a quantum mechanical framework, and indeed, there may be no necessity to do so. Instead, it is typically described within the context of a Spiking Neural Network (SNN). Although Schrödinger equation does not have the spiking phenomenon, both quantum systems and SNNs exhibit a shared trait: they function as oscillator systems. In this presentation, drawing from our ongoing research, we will bridge the temporal dynamics of a network of LIF (Leaky Integrate-and-Fire) neurons to the quantum dynamics of qubits. In general, the Schrödinger equation of O(n) qubits can be unraveled into the neuronal dynamics of O(2^n) LIF neurons. In principle, the time complexity of such emulation is linear in the quantum evolution time. Neuromorphic computing is inspired by the biological brain, and a single neuromorphic chip currently contains approximately 100 million neurons. Consequently, our research presents an opportunity to leverage neuromorphic chips for simulating large-scale, complex quantum dynamics.