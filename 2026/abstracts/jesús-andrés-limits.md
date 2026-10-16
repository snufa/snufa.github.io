# Limits of Local Credit Assignment in Recurrent Neural Networks

**Authors:** Jesús Andrés Espinoza-Valverde, Gustavo Ramirez-Hidalgo
                           
**Presenting author:** Jesús Andrés Espinoza-Valverde

**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

When are the recurrent dependencies discarded by local learning actually negligible? Eligibility propagation (e-prop) provides a biologically plausible approximation to recurrent gradient learning by neglecting explicit recurrent dependencies among neurons. Previous work has formalized this approximation within a hierarchy of higher-order recurrent learning rules, termed m-order e-prop. Here we address the conditions under which this truncation remains accurate by analyzing and quantifying how network structure and dynamics control the discrepancy between local and exact recurrent credit assignment.

We derive deterministic bounds on the gradient gap between order-truncated learning and the exact BPTT gradient. These bounds identify an effective recurrence factor that captures both the growth of available recurrent paths and the dynamical gain along each transition, and establish a sufficient regime in which higher-order contributions decay geometrically with recurrent order (m).

We test these predictions numerically by independently varying sparsity, recurrent weight scale, and activation slope. In all three cases, reducing effective recurrent propagation systematically closes the gap between e-prop and BPTT and increases their gradient alignment. Thus, sparsity, synaptic strength, and neuronal gain act as distinct mechanisms controlling the importance of nonlocal recurrent credit.

These results shift the focus from how to construct increasingly accurate nonlocal approximations of recurrent gradients to when such higher-order recurrent information is needed at all. This perspective provides a framework for identifying regimes in which globally defined recurrent credit assignment becomes effectively local, and for understanding how network structure and dynamics determine the limits of local credit assignment in recurrent and spiking neural networks.