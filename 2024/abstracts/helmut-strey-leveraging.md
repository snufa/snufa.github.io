# Leveraging physics-informed neural networks to extend single neuron models with patch-clamp data

**Authors:** Anthony G. Chesebro, David Hofmann, Vaibhav Dixit, Lilianne R. Mujica-Parodi, Helmut Strey
                           
**Presenting author:** Anthony Chesebro

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Computational neuroscience approaches are built upon a foundation of single neuron models. Beginning with the Hodgkin-Huxley model, researchers have developed increasingly complex models that incorporate a variety of factors to better understand the behavior of individual neurons. A key ingredient in these approaches, however, is the reliance upon the model's creators to know and apply different mathematical approaches. The original Hodgkin-Huxley model, for example, relied on the authors knowing to combine electrical circuit models with Boltzmann equations for the sodium and potassium activation/inactivation gating functions. In modern experiments, however, it can be difficult to know a priori which expressions will accurately model new experimental data, and committing to specific hypotheses can lead to an overly narrow model development pipeline.

In this work, we discuss three extensions to single neuron modeling approaches when presented with new data. First, we show how a physics-informed neural network (PINN) can be used to recover new states in the Hodgkin-Huxley formalism directly from experimental data. We combine several learning approaches to efficiently train the PINN, tuning the learning with summary statistics to avoid overfitting noisy experimental data. Secondly, we apply symbolic regression to directly recover an analytical expression of the learned dynamics, which is typically more generalizable to new experimental data than the PINN itself would be. Finally, we use these approaches to probe experimental data of patch-clamp recordings of neurons in the presence of altered glucose availability. Neurons' ability to maintain their reversal potentials is known to be affected by ATP supply. Using this method, we show how this method can be used in experiments by providing an automated way to derive an expression directly from data for how glucose availability changes traditional Hodgkin-Huxley dynamics. 