---
id: 2026-07-04 11:01:32
title: Hh Sensitivity Indices Kinetics
topic: neuroscience
type: literature
source: raw/hh-sensitivity-indices-kinetics.md
tags: []
created: 2026-07-04
---

## Idea
# Sobol Sensitivity in Neuronal Excitability

Global sensitivity analysis using **First-order Sobol sensitivity indices** reveals how individual kinetic parameters in the Hodgkin-Huxley model contribute to the variance of neuronal output over time [[korngreen-population-modeling-hh]].

## Findings

- **Time-Dependent Variance**: All kinetic parameters contribute to output variance in a strongly time-dependent manner.
- **Transient vs. Steady-State**: Distinct parameters control behavior at different stages; for instance, specific subsets of parameters dominate transient vs. steady-state responses for both sodium and potassium conductances.
- **Uniformity During Spiking**: During active spiking, sensitivity analysis shows a more uniform contribution across parameters, suggesting a high-dimensional coordination of kinetics during the action potential itself.

## Topological Significance
This suggests that the "state space" of excitability is not equally sensitive to all parameter shifts at all times; rather, the system's trajectory is constrained by different sub-manifolds of the parameter space depending on the phase of the firing cycle.

## Related
- [[hh-parameter-degeneracy-robustness]]
- [[korngreen-population-modeling-hh]]

## Why it matters
Restructured during 2026-07-04 migration to Zettelkasten format.

## Connections
- Migrated from raw/hh-sensitivity-indices-kinetics.md

## Open questions
- Needs deeper linking to the new slip-box structure.

## Source
raw/hh-sensitivity-indices-kinetics.md
