# Simulating Neural Drift via Perceptual Sampling

## CORnet-S as a Neural Proxy
To test if behavioral drift alone can cause representational drift, fixation-masked images (based on human gaze data) are passed through **CORnet-S**, a hierarchical deep neural network modeled on the primate ventral visual stream.

## Layer-Wise Drift Characteristics
Representational distances (Frobenius norm of activation differences) increase with temporal separation across all model layers:
- **V1 & V2**: Early sensory representations reflect sampling shifts.
- **V4 & IT**: Higher-level object representations also drift, inheriting and potentially amplifying the sampling changes.

## Maximum Mean Discrepancy (MMD)
A kernel-based **MMD test** confirms that the distribution of representational distances induced by real gaze drift is significantly different from shuffled controls. This proves that the specific, systematic nature of human gaze shifts—rather than just random movement—is the driver of the simulated neural drift.

---
**Source:** [[Yuan et al. (2026) — Changes in perceptual sampling contribute to representational drift]]
**Clusters:** [[Neural Manifolds]], [[Linear Algebra of Subjective Experience]]
