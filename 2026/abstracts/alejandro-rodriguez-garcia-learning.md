# Learning sensorimotor representations through active event-based foveated sensing

**Authors:** Alejandro Rodriguez-Garcia, Anindya Ghosh, Arthur Aubret, Srikanth Ramaswamy, Giulia D'Angelo
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

From infancy, humans learn to recognise objects through active sensorimotor exploration. Sensorimotor contingency theory grounds perception in the coupling between exploratory actions and their sensory consequences. Yet most computer vision learning pipelines remain passive, and active glimpse-based methods encode fixation locations rather than the ego-motion transformations linking successive views, leaving the embodied sensory-action loop only partially leveraged. Moreover, as successive observations of the same object increase the storage and processing burden of dense sensory data, neuromorphic vision provides a sparse alternative, offering an efficient substrate for this embodied process.

We introduce an embodied active vision framework built around the characterised ICNS simulator. During fixation, drift and microsaccades generate events from stationary objects, driving a learning-free spiking attention mechanism whose attentional gain balances exploration and selection of salient regions, reached through saccades. Saccadic events are suppressed, and each fixation yields a foveated glimpse, producing observation sequences linked by the executed ego-motion. The simulated FOVEA-4K dataset (4,000 3D objects, 105 categories) has only 3.02% spatial occupancy and requires 18.7× less storage per glimpse than its RGB counterpart.

We use these sequences to develop action-predictive contrastive learning through time (AP-CLTT), which learns egocentric object representations structured by predictive sensorimotor relationships.   We benchmark AP-CLTT against vanilla CLTT and its action-aware counterpart (AA-CLTT), evaluating generalisation both to new glimpses of familiar objects and to novel objects. AA-CLTT favours object-level abstraction, whereas AP-CLTT generalises more strongly across glimpses of the same object with comparable object-recognition performance. Both action-conditioned approaches outperform CLTT, especially with few fixations, suggesting that action information improves representation efficiency.

We close the sensorimotor loop by using this learned forward model to provide a top-down signal guiding next-fixation selection to increase the representational coverage of the object, illustrating how ego-motion can bridge self-supervised representation learning and active sensing in neuromorphic vision.