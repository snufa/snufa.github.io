# Where forgetting lives in a spiking continual-learning memory

**Authors:** Anindya Ghosh, Alejandro Rodriguez-Garcia, Srikanth Ramaswamy
                           


**Presentation type:** Talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Animals learn throughout life without erasing what they know. They are never told when one learning episode ends, do not replay all their past experiences, and do not send errors back through their memories – shortcuts that most machine continual learning relies on. The hippocampus suggests another route: in behavioural-timescale synaptic plasticity (BTSP), a single dendritic plateau potential strengthens every synapse active within a few seconds of it, storing an input in one exposure from signals local to the neuron.

We built a spiking memory on this rule. A front-end trained once and frozen – like a hardwired sensory cortex – uses spikes from spoken digits (SHD), spoken words (SSC) or gestures (DVSGesture) to drive adaptive integrate-and-fire neurons of differing excitability. A neuron writes only when its dendrite plateaus, in one step, and never overwrites. Neuromodulators act on neurons, not synapses: surprise raises noradrenaline, which makes plateaus more likely, while acetylcholine sets how many plateauing neurons write. Local BTSP alone effects weight changes, so learning is online, spatio-temporally local and boundary-free – no task labels, boundaries, replay or back-propagated errors reach the memory.

The engram is therefore written one-shot and label-free, and never overwritten, so the memory never decides which past engram to update or where to overwrite – it only recruits, and because one global excitability signal drives recruitment, choosing among plateauing neurons at random stores as well as matching them to content. Categories accumulate instead via a supervised read-out updated on every labelled instance: a read-out that merely averages each category's response outperforms elastic weight consolidation (EWC), synaptic intelligence (SI), and experience replay at mitigating catastrophic forgetting on all three datasets. No stored synapse ever changes, yet the code of old inputs drifts, because neurons recruited for new categories also come to respond to older ones.

Forgetting here lies outside storage and capacity: a trivial read-out recovers the stored memories, and recruiting new neurons – the operation that neurogenesis-style methods add to expand capacity – is itself what makes old codes drift. The limiting factor for brain-like continual learning is not protecting synapses or adding neurons, but inferring which context an input belongs to.
