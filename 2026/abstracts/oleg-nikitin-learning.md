# Learning quadruped and hexapod gaits through predictive spiking control of neuromodulated CPGs

**Authors:** Oleg Nikitin, Olivia Lukyanova, Alex Kunin
                           
**Presenting author:** Oleg Nikitin

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Flexible locomotion requires rhythmic motor circuits to remain coordinated while their outputs change with sensory context. We present a hierarchical spiking architecture in which predictive-coding cortical networks regulate interacting populations of neuromodulated central pattern generators (CPGs). Motor populations generate joint-level activity, while coordinator populations exchange spikes with motor populations to organize interjoint dynamics. Spatially distributed, opposing neuromodulatory signals reshape oscillator activity and the information transmitted between populations.

The cortical controller comprises neurons with learned causal temporal filters, leaky membrane integration, and adaptive spike thresholds. Distinct populations represent sensory and motor context, predict changes in task outcomes, and predict the residual errors of these outcome forecasts. Local prediction-error updates optimize temporal filtering, while outcome-modulated eligibility assigns credit to changes in the controller interfaces. This separates learning the temporal structure of sensorimotor signals from learning how actions affect task performance.

We optimize CPG populations for input responsiveness, reproducible chemical modulation, and effective downstream influence. With the selected oscillator circuitry fixed, the predictive spiking controller adapts sensory-to-CPG projections, neuromodulator release, coupling between populations, and CPG-to-action readouts. Electrical interactions provide rapid coordination, whereas chemical state changes the available motor dynamics and their contextual expression.

We demonstrate the architecture in the Gymnasium Ant locomotion RL benchmark and on a physical hexapod robotic platform. The resulting controller generates coordinated movement through the interaction of sensory feedback, predictive adaptation, and neuromodulated rhythmic activity. These results link local predictive computation to distributed motor coordination and establish interacting CPG populations as reusable dynamical substrates for adaptive spiking control.