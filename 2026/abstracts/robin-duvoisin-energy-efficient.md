# Energy-Efficient Neural Coding under Uniform and Heavy-Tailed Input Distributions

**Authors:** Robin Duvoisin, Jean-Pascal Pfister, Pau Vilimelis Aceituno
                           
**Presenting author:**  

**Presentation type:** Talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Around 50–80% of neurons’ energy is spent on generating and transmitting neural activity (Laughlin 2001). This raises a fundamental question: how sparse should a neural population be to encode a set of stimuli at minimal energetic cost? At one extreme lies the “grandmother” code, in which each stimulus activates a single neuron; at the other lies a denser code that favors combinatorial capacity (Levy & Baxter 1996). The optimal trade-off depends on the technology or type of neuron considered: if activation is expensive relative to the neuron’s maintenance cost, one-hot encoding is favored, whereas a lower relative activation cost favors denser codes. Our project aims to determine these regimes as a function of the relative cost of activation.
For uniformly distributed stimuli, we first formulate the problem as minimizing cost over population size and the number of active neurons, while ensuring that all stimuli can be represented. In the asymptotic limit, we show that this combinatorial optimization maps onto a cost-constrained channel-coding problem. This mapping relates the relative cost of activation to the optimal fraction of active neurons, revealing a transformation from dense to sparse coding as signaling becomes expensive.
Second, we relax the assumption of uniformly distributed stimuli, giving rise to a probabilistically modulated encoder. More frequent stimuli are encoded at lower energetic cost, thereby adapting the code to input statistics. Using a similar channel-coding mapping, we derive the optimal fractions of active neurons.
Together, these results connect neural population coding with classical information theory and provide a framework for predicting energy-efficient population activity from stimulus statistics and signaling costs. These advances in theoretical neuroscience may also guide the design of neuromorphic systems by identifying the activity fraction that minimizes energetic cost, while providing a reference point for comparing the energy efficiency of different devices (Davies 2019).
