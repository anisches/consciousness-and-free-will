# DRIADA: A Python Toolkit for Cross-Scale Analysis of Single-Neuron Selectivity and Population Dynamics

**Reference**: Pospelov, N., Plusnin, V., Rogozhnikova, O., Ivanova, A., Sotskov, V., Orobets, M., Toropova, R., Ivashkina, O., Avetisov, V., & Anokhin, K. (2026). DRIADA: A Python Toolkit for Cross-Scale Analysis of Single-Neuron Selectivity and Population Dynamics. *arXiv:2607.00851v1*.

## Overview

DRIADA is an open-source Python framework designed to bridge the gap between single-neuron and population-level neural analysis. It unifies neural signals (calcium imaging, spike trains, simulations) and time-aligned behavior into a shared data model. This unification allows for a seamless workflow encompassing:
1. **Selectivity Testing**: Quantifying how individual neurons respond to behavioral features.
2. **Dimensionality Reduction**: Mapping high-dimensional population activity onto low-dimensional [[neural manifolds]].
3. **Network Analysis**: Investigating the topological structure of neural representations.

## Key Capabilities

- **Cross-Scale Integration**: Facilitates moving between paradigms (e.g., from place cells to hippocampal manifolds) without data format friction.
- **Unified Workflow**: Operates within a shared data model where behavior and neural dynamics are inherently linked.
- **Benchmarking**: Validated against synthetic ground truth, mouse hippocampal calcium imaging, and simulated toroidal attractor networks.

## Findings

### Hippocampal Spatial Embedding
In hippocampal calcium imaging data from 13 mice in an open field, DRIADA was used to apply [[selectivity-based manifold filtering]]. By filtering neurons based on their spatial selectivity, the toolkit successfully restored a two-dimensional spatial embedding from an otherwise collapsed all-neuron embedding.

### Non-Selective Manifold Contribution
A "reverse analysis" revealed that approximately **57% of neurons** that were highly informative about the leading dimensions of the neural manifold were **not selective** for any of the 11 measured behavioral features. This suggests that a significant portion of the population contributes to the latent structure of representation without exhibiting classical tuning to individual external variables. See [[non-selective manifold neurons]].

### Topological Recovery
On a simulated toroidal attractor network benchmark, four independent modules within DRIADA successfully recovered the expected toroidal topology, demonstrating its robustness in identifying complex latent structures.

---
**Tags**: #neuroscience #computation #neural-manifolds #dimensionality-reduction #DRIADA #software-toolkit
**Related**: [[cross-scale neural analysis]], [[selectivity-based manifold filtering]], [[non-selective manifold neurons]]
