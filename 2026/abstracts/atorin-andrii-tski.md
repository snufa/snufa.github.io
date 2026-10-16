# TSKI 5: A Bio-Inspired Discrete Temporal Neural Network Model without Gradient Descent or a Global Error Function.

**Authors:** Atorin Andrii 
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

We present TSKI 5 (Theory of Synaptic Information Coefficients), a bio-inspired discrete temporal neural network model designed for adaptive learning in continuously changing environments without gradient descent, backpropagation, or a global loss function.
 
The model is based on a periodic neuron operation algorithm consisting of reception and transmission phases. Rather than representing a stimulus primarily through instantaneous amplitude, TSKI encodes information through temporal dynamics, including the duration of the reception phase (Δt), its changes between successive periods, neuronal frequency W, and synchronization between neurons. Relative refractoriness introduces network-dependent variability in phase transitions: the end of a neuronal period can depend on the activity of other neurons. Thus, stochasticity-like behavior can emerge from discrete temporal interactions rather than from externally injected noise.
 
Learning is implemented through local structural plasticity. The synaptic strength coefficient Cij is modified according to the change in a neuron's normalized information contribution between successive transmission periods. When the coefficient crosses predefined bounds, local structural operations (Copy/Delete) modify the connectivity of the network. Consequently, adaptation is driven by the temporal statistics of network activity rather than by propagation of a global error signal.
 
A central hypothesis of TSKI is that repeated statistically similar stimuli can produce recurrent quasistable neuronal dynamics. Such recurrence may exert repeated structural pressure on the network, allowing a structural core to emerge that is capable of reproducing corresponding quasistable responses. An additional internally driven regime is proposed to test and restructure the learned connectivity, providing a mechanism for adaptation beyond direct external stimulation.
 
The model yields explicit, experimentally testable hypotheses concerning temporal coding, emergent stochasticity, quasistability, structural plasticity, and continual adaptation. We propose computational experiments comparing TSKI with conventional gradient-based and biologically plausible local-learning approaches.