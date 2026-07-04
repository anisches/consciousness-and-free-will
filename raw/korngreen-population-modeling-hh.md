# Korngreen Population Modeling (HH)

Korngreen (2026) introduced a method for embedding uncertainty and global sensitivity analysis directly into the construction of the Hodgkin-Huxley model, shifting from a deterministic "best-fit" pipeline to a population-based approach.

## Methodology

- **Uncertainty Reintroduction**: Digitized original sodium and potassium rate-constant data from Hodgkin & Huxley (1952) and used bootstrap resampling to estimate uncertainty in voltage-dependent kinetic parameters.
- **Monte Carlo Propagation**: Propagated uncertainty estimates through a spatially extended squid axon cable model. Each sample in the simulation defined a unique set of kinetic, conductance, passive, and structural parameters.
- **Population Heterogeneity**: The resulting population showed a diverse range of firing behaviors: non-firing, phasic, regular, and spontaneous activity.

## Implications for Agency
If neuronal behavior is a population property emerging from degenerate parameters, then biological "choice" or response-tendency is more robust than a single deterministic causal chain would suggest. This aligns with [[mitchell-noble-top-down-causation-agency]]'s view of organisms as organized systems constraining their components.

## Related
- [[hh-parameter-degeneracy-robustness]]
- [[hh-canonical-model-reassessment]]
- [[sobol-sensitivity-in-neuronal-excitability]]
