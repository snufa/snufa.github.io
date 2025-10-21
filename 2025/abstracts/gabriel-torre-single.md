# Single Spiking Neural Network with Neuromodulated Attractors for Adaptive Robotic Quadruped Gait Switching

**Authors:** Gabriel Torre, Juan Giribet, Sergio Lew
                           
**Presenting author:** Gabriel Torre

**Presentation type:** Flash talk at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking neural networks (SNNs) are theoretically universal function approximators, but embodying that universality in real-world robotic control remains underexplored. We present a novel architecture in which a recurrent clustered SNN, modulated by global dopamine signals, realizes multiple motor patterns, gaits, in a single network. Each gait (e.g., bound, trot, as well as exploration or quiescence) corresponds to a distinct attractor in network dynamics. By adjusting dopamine, the network changes its excitation-inhibition balance and shifts across attractors without needing retraining or separate modules.

We integrate a reward feedback signal that adapts dopamine level during locomotion, enabling the robot to learn which gait to select under different conditions, and to transition smoothly between them. We thoroughly evaluate the model on a physical quadruped robot, demonstrating that the desired gaits sustain stable locomotion metrics comparable to tuned classical CPG-based controllers.

By combining neuromodulation, attractor dynamics, and embodied validation, this work illustrates how a single spiking network can approximate a family of control functions, adaptively switch between them, and do so in a real robot.