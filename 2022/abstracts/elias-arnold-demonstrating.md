
# Demonstrating a fully automated software framework for PyTorch-based training on BrainScaleS-2 using a high-speed data communication example

**Authors:** Elias Arnold, Eric Müller, Philipp Spilger

**Presentation type:** Poster

## Abstract

We present our work towards a PyTorch-integrated general-purpose modeling framework for BrainScaleS-2 (BSS-2).
While previous efforts either focused on the rate-based operation mode of BSS-2 or lacked full automation, our approach enables the training of spike-based networks (SNNs) within PyTorch including support for auto differentiation in a fully-automated hardware experiment workflow.
Moreover, our framework facilitates seamless transitions between emulating on hardware and simulating in software.
To demonstrate the capabilities of our software library, hxtorch.snn, in a real-world application, we investigate the usage of SNNs on our accelerated neuromorphic hardware system BSS-2 for energy-efficient digital signal processing (DSP) in high-speed optical communication systems.
We implement an SNN equalizer to compensate for non-linear impairments in a temporal sequence transmitted in an simulated optical short-reach intensity-modulated / direct-detection (IM/DD) link.
Our implementation employs Back-Propagation-Through-Time (BPTT) with surrogate gradients for training, and outperforms —in software and on hardware— linear equalization in terms of achieved bit error rate (BER) with only a small hardware penalty.