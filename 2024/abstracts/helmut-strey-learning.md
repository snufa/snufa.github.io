# Learning novel, sparse neural masses directly from spiking networks using universal differential equations

**Authors:** Anthony G. Chesebro, David Hofmann, Vaibhav Dixit, Lilianne R. Mujica-Parodi
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Neural mass models offer a promising path forward for bridging the gap between detailed spiking models and macroscopic brain activity. Traditional neural mass models, like the Jansen-Rit and Larter-Breakspear neural masses, have typically been built in a quasi-phenomenological approach to capture specific microscale mechanisms without an analytical approach to tie them to emergent macroscale effects. Thus, while they offer targeted explanatory abilities for specific questions, they fail to fully capture the properties that emerge from spiking neuron populations.

Next-generation neural mass models offer a promising way to analytically derive novel neural mass representations directly from the known form of spiking neurons. This approach leverages the Ott-Antonsen ansatz to derive an analytical mean-field expression for the entire population. This is helpful because it connects the neuron's small-scale properties (like burstiness) directly to its large-scale expression. This can lead to new properties like theta-driven gamma bursts that are harder to detect in neural masses. One important caveat of the next-generation neural mass approach is that it assumes all-to-all connectivity. While this is an approximately accurate assumption for the hippocampal areas these were first derived to model, it is obviously invalid in the cortex. 

In this work, we leverage universal differential equations, combined with symbolic regression, to infer the proper correction terms for sparsity in next-generation neural mass models. Physics-informed neural networks have been used to learn novel equations in different physics domains. In this work, we extend them to deriving new forms of next-generation neural masses with arbitrary levels of sparsity. By simulating large neuron populations at different levels of sparsity and different connectivity structures, we provide a robust training set to learn the expressions of new neural masses. We then compare these automated, hypothesis-free results to the analytical shortcuts adopted in newer approaches to satisfy the Ott-Antonsen ansatz assumptions.