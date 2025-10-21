# Hyperparameter Estimation to Improve Spiking Neural Networks' Learning

**Authors:** Jhon Intriago, Pablo A. Estévez
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking Neural Networks (SNNs) are a kind of Artificial Neural Networks (ANNs) that have proven to be efficient and fault-tolerant in solving different real-world problems. SNNs were designed to replicate to some degree the functionality of biological neurons in the human brain, especially in the way they convey information (binary pulses also known as spikes).

The spiking property of SNNs enhances their biological plausibility over traditional ANNs. However, accurately estimating hyperparameters, such as the membrane potential threshold, remains challenging, partly due to the lack of suitable methods to address this problem. For that reason, we propose a new heuristic method to reduce the complexity of hyperparameter estimation based on the network architecture and the length of the sequence.

The proposed method was evaluated in the Spiking Heidelberg Digits dataset with 700 dimensions and 0.01ms simulation time (100 sequence length). It achieved 93.33±0.6% accuracy, improving the Symplectic Euler-based adaptive SNN baseline by 1.74%. With a 0.004ms simulation time (256 sequence length), it achieved 93.14±0.5% accuracy, improving the baseline by 1.84%. In addition, SNNs with the estimated hyperparameters are robust to gradient problems and converge faster than SNNs with arbitrary hyperparameter selection. 

We demonstrate that SNN hyperparameters can be systematically determined using a heuristic method, applicable to a range of architectures.