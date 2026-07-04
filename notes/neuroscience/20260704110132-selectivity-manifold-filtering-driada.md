---
id: 2026-07-04 11:01:32
title: Selectivity Manifold Filtering Driada
topic: neuroscience
type: permanent
source: Internal Migration
tags: []
created: 2026-07-04
---

## Idea
# Selectivity-Based Manifold Filtering

**Selectivity-based manifold filtering** is a technique introduced/formalized in the [[DRIADA toolkit]] (Pospelov et al., 2026) for refining the visualization and analysis of [[neural manifolds]] by incorporating single-neuron behavioral tuning.

## Concept

Traditional dimensionality reduction (e.g., PCA, UMAP, PHATE) often uses the entire recorded population. However, in large-scale recordings (like calcium imaging), the manifold structure of interest (e.g., a spatial map) can be obscured by noise or "distractor" neurons that are not selective for the variables under study.

Selectivity-based filtering involves:
1. Identifying neurons with statistically significant selectivity for specific behavioral features (e.g., place, head direction, speed).
2. Using only this subset (or weighting them) for dimensionality reduction.
3. This process can "de-noise" the latent representation and reveal the underlying topology that aligns with the behavioral task.

## Case Study: Hippocampal spatial embeddings

In mouse hippocampal data (open field), an embedding using all recorded neurons often appears collapsed or unstructured due to the high percentage of non-selective or weakly selective neurons. Using DRIADA's filtering module, researchers were able to restore a clear two-dimensional spatial embedding that accurately reflected the mouse's physical environment.

## Implications for Agency

This technique highlights the tension between **latent representation** and **behavioral readout**. If the "manifold of interest" only appears when we filter for behavior, what is the rest of the neural population doing? This raises questions about whether "agency" and "decisions" are driven by the behaviorally-aligned manifold or if the non-selective components represent a broader, unmeasured state-space of the organism.

---
**Tags**: #neuroscience #topology #neural-manifolds #dimensionality-reduction #DRIADA
**Related**: [[pospelov_driada_toolkit_2026]], [[non-selective manifold neurons]]

## Why it matters
Restructured during 2026-07-04 migration to Zettelkasten format.

## Connections
- Migrated from biology/neuroscience/computation/selectivity_manifold_filtering_driada.md

## Open questions
- Needs deeper linking to the new slip-box structure.

## Source
biology/neuroscience/computation/selectivity_manifold_filtering_driada.md
