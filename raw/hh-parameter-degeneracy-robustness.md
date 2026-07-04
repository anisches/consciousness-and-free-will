# HH Parameter Degeracy and Robustness

Biophysically detailed models like the Hodgkin-Huxley (HH) model exhibit significant **parameter degeneracy**, where disparate sets of kinetic and conductance parameters can yield functionally similar or biologically relevant output behaviors [[korngreen-population-modeling-hh]].

## Key Concepts

- **Degeneracy in Excitable Systems**: Robustness in neuronal firing does not depend on a single "perfect" parameter set but on the overlapping influence of multiple channel properties.
- **Robustness through Heterogeneity**: By propagating fitted-parameter uncertainty through Monte Carlo simulations, Korngreen (2026) demonstrated that a wide range of parameters can maintain action potential propagation and conduction velocity within experimental ranges.
- **Relativity of the "Canonical"**: The original 1952 HH parameter set is a "minority subpopulation" focused on regular firing, while the dominant behavior in a population-based model is phasic firing (single-spike escape response).

## Related
- [[hh-canonical-model-reassessment]]
- [[marder-crab-thermal-compensation-homeostasis]]
- [[hh-sensitivity-indices-kinetics]]
