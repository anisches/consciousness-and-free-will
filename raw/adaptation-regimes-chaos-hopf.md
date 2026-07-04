# Adaptation Regimes and Instability Mechanisms

- **Source**: [[zheng-low-rank-adaptation-oscillations.md]]
- **Topics**: [[hopf-bifurcation]], [[chaos-onset]], [[stochastic-switching]], [[limit-cycles]]

## The Four Regimes of Adaptation

When random connectivity is strong enough to generate chaos ($g > 1$), increasing the strength of activity-dependent adaptation drives the network through four phases:

1. **Static Coherent State**: The low-rank mode is stable; activity is steady.
2. **Noise-sustained Oscillations**: Chaos provides the "noise" that kicks the coherent mode into regular or irregular oscillations.
3. **Stochastic Switching**: The system switches between symmetric wells (bistability) driven by the internal "stochasticity" of the chaotic background.
4. **Global Limit Cycle**: Adaptation is strong enough to drive a stable, high-amplitude population oscillation (Hopf bifurcation).

## Bifurcation Structure

The paper identifies a reduced 3D model that captures the essential bifurcation structure. The competition between the **Chaos Onset** (intrinsic to the random weights) and the **Hopf Bifurcation** (intrinsic to the low-rank + adaptation loop) is mediated by the frequency-dependent single-neuron transfer function.

## Theoretical Significance

This suggests that biological states (like different stages of sleep or levels of anesthesia) might correspond to different "tuning" parameters of this adaptation-low-rank interaction, allowing a single architecture to produce widely different dynamical regimes.

---
*Created: 2026-07-01*
