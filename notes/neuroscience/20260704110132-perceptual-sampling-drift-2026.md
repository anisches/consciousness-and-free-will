---
id: 2026-07-04 11:01:32
title: Perceptual Sampling Drift 2026
topic: neuroscience
type: permanent
source: Internal Migration
tags: []
created: 2026-07-04
---

## Idea
# Changes in perceptual sampling contribute to representational drift

**Authors:** Yixin Yuan, Mikio Christian Aoi, John Serences
**DOI:** 10.64898/2026.06.24.734121
**Source:** bioRxiv (Neuroscience)
**Date:** 2026-06-30

## Overview

This paper challenges the prevailing view that **representational drift**—the gradual decay of neural pattern stability over time—is exclusively caused by internal brain dynamics like synaptic turnover. By combining longitudinal eye-tracking in humans with deep neural network modeling (CORnet-S), the authors demonstrate that systematic shifts in behavior, specifically how humans sample visual scenes (gaze patterns), are sufficient to drive representational drift in the absence of intrinsic neural reconfiguration.

## Key Findings

- **Directional Gaze Drift**: Fixation density maps for naturalistic images become increasingly dissimilar over a 2-4 week period. This drift is not stochastic but follows a systematic trajectory over time.
- **Quantification via Wasserstein Distance**: The similarity of perceptual sampling maps was rigorously measured using Wasserstein distance, showing a clear temporal decay in sampling consistency.
- **Simulation of Neural Impact**: Passing fixation-masked images through **CORnet-S** (V1, V2, V4, and IT layers) produced representational drift patterns that mirrored empirical observations in cortical areas.
- **Systematicity over Noise**: A kernel-based Maximum Mean Discrepancy (MMD) test confirmed that the drift was driven by the structured nature of behavioral changes rather than random noise.

## Implications for Agency

This research suggests that what we perceive as "neural drift" may in part be a stable neural response to a drifting behavioral policy. It highlights the role of **active sampling** as a core component of neural representation, suggesting that the "self" as a controller of attention is a significant driver of neural state-space trajectories.

## Atomic Notes
- [[../../../raw/behavioral-contribution-representational-drift.md]]
- [[../../../raw/perceptual-sampling-wasserstein-drift.md]]
- [[../../../raw/cornet-s-neural-drift-simulation.md]]

## Related
- [[../invertebrates/ant_scanning_circuits_2026.md]] (Active sampling in insects)
- [[color_perception_dnn_2026.md]] (Representational alignment)
- [[../../../raw/animal-agency-experiments.md]]

## Why it matters
Restructured during 2026-07-04 migration to Zettelkasten format.

## Connections
- Migrated from biology/neuroscience/computation/perceptual_sampling_drift_2026.md

## Open questions
- Needs deeper linking to the new slip-box structure.

## Source
biology/neuroscience/computation/perceptual_sampling_drift_2026.md
