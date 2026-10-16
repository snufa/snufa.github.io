# Analyzing Surrogate Gradient Training Stability in Spiking Neural Networks Using Dynamical Systems Theory

**Authors:** Kevin Karim
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Spiking Neural Networks (SNNs) offer a more biologically plausible alternative to traditional Artificial Neural Networks (ANNs). However, the threshold used to trigger spikes is problematic for gradient-based optimization. One way of training them is by using Surrogate Gradient (SG) which replaces the spike threshold with a smooth approximation during the backward pass to enable training with Backpropagation Through Time (BPTT). Still, like Recurrent Neural Networks (RNNs), SNNs can suffer from the problems of vanishing and exploding gradients.  

This work studies gradient stability in SNNs trained with SG. We calculate Surrogate Lyapunov Exponents (SLEs) from the surrogate Jacobian as a diagnostic of long-term gradient propagation. Further, we use Surrogate Gradient Flossing (SGF), inspired by Gradient Flossing (GF), as a method for controlling the SLEs and moving the networks toward a regime of stable long-term gradient propagation. To evaluate this approach, we designed a classification task that targets temporal credit assignment over long time horizons, and compared networks trained with and without SGF under increasing temporal task delays and network depth.

We find that the exponential divergence predicted by the largest SLE is approximately proportional to the long-term gradient norm across many orders of magnitude. Further, we show that SGF can move the leading SLEs toward a regime of stable gradient propagation. However, the effect of SGF on classification performance is more nuanced. Under increasing temporal delay, we find that most of its benefits can be attributed to tuning the SG slope. Under increasing network depth, we find that controlling the leading SLEs is insufficient to prevent the gradient norm from vanishing. In conclusion, the largest SLE provides a useful diagnostic of long-term gradient propagation in SNNs trained with SG, although controlling the leading SLEs is not sufficient to guarantee trainable networks.
