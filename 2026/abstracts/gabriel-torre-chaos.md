# Chaos as Exploration: Dopamine-Modulated Spiking Attractors That Discover How to Walk on a Real Robot

**Authors:** Gabriel Torre, Juan Giribet, Sergio Lew
                           
**Presenting author:** Gabriel Torre

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Recurrent spiking networks are usually tuned to avoid chaos, yet biological motor systems seem to exploit variability to discover new behaviors. In previous work, we showed that a single clustered network of leaky integrate-and-fire (LIF) neurons can express multiple quadruped gaits as distinct attractors, selected by a global dopamine signal. Here, we ask whether the network's chaotic regime can serve as an exploration engine for learning directly from the environment.

First, we characterize the network's dynamics. At low dopamine, weakened inhibition drives the network into chaos, with a positive maximal Lyapunov exponent: activity wanders across attractor basins until rising dopamine collapses it onto stable limit cycles. Dopamine thus acts as a single, biologically grounded knob that trades exploration for exploitation.

Second, we close the loop. Previously, reward was computed from the network's own spiking activity. We now introduce a hierarchical architecture inspired by the basal ganglia–spinal cord axis. A high-level spiking population handles selection and modulation, a spiking central pattern generator produces rhythms, and a PD controller handles execution. Dopamine is driven by reward from the body's interaction with its environment. In a simple simulated organism, the network first explores chaotically and then settles into effective locomotion as reward rises, with fixed synaptic weights: all adaptation happens through neuromodulated dynamics.

Third, we are bringing the gait-switching controller from our small servo-driven prototype to a Unitree Go2 quadruped, and will present early hardware results. Next, we plan to replace the hand-designed foot trajectories with patterns learned through supervised STDP.

Together, these results suggest that a fixed recurrent spiking network can be steered through its own dynamical repertoire by a neuromodulatory reward, with chaos as a resource rather than a nuisance. We discuss the limits of this approach and the path toward closed-loop reward learning on real robots.