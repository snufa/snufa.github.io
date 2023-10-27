# Training Spiking Neural Networks for Continuous Control with Surrogate Gradients

**Authors:** Justus Huebotter, Pablo Lanillos, Serge Thill, Marcel van Gerven

**Presentation type:** Short talk

## Abstract

While humans control their limbs using spiking patterns, learning to control robots from scratch with Spiking Neural Networks (SNN) remains an open challenge. Here, we utilised surrogate gradients to craft a network architecture tailored for low-level continuous robotic control, drawing inspiration from both optimal control theory and the concept of the predictive brain. We evaluated the model in a "reach & follow" task with a simulated 2 DoF planar arm and a 7 DoF Franka Panda robot.

Our architecture integrates a recurrent prediction network (forward model) that learns state transitions and a policy network (inverse model) for control signal generation using leaky integrate-and-fire neurons. Population-based spike encoding and decoding enable our networks to seamlessly handle continuous variable vectors. This design facilitates autoregressive imagination of state-action trajectories, essential for end-to-end learning. A significant challenge was the vanishing gradients during the autoregressive network prediction loop. To ensure stable learning, we employed techniques like neural manifold restraint through low-rank weight matrix decomposition, fluctuation-driven weight initialisation, and spike regularisation.

Comparisons against optimal control baselines and non-spiking probabilistic neural network models underscore the competitive prowess of our SNN approach. Envisioning broader application horizons, we developed an open-source SNN control library based on the Stork framework. We further aim to augment the low-level controller with spiking reinforcement learning, targeting complex tasks like air hockey or table tennis, which demand a blend of precision, adaptability, and strategy.