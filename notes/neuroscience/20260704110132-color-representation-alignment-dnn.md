---
id: 2026-07-04 11:01:32
title: Color Representation Alignment Dnn
topic: neuroscience
type: literature
source: raw/color-representation-alignment-dnn.md
tags: []
created: 2026-07-04
---

## Idea
# Representational Alignment of Color Perception: Humans vs. DNNs

## The Problem of Large-Scale Perception
Exploring the global representational structure of thousands of colors in humans is psychophysically infeasible. Deep Neural Networks (DNNs) serve as potential proxies, but their geometric alignment with human perception depends heavily on their learning paradigm.

## Learning Paradigms and Alignment
A systematic comparison of [[Self-Supervised Learning]], [[Supervised Learning]], and [[CLIP]] embeddings against human similarity judgments reveals:
- **Early Layer Convergence**: All paradigms (SSL, SL, CLIP) align well with human color data in early layers (fine-item level).
- **Output Layer Divergence**: Only [[CLIP]] sustains a human-congruent color representation at the output layer.
- **Large-Scale Predictions**: DNNs trained on image-text pairs (CLIP) provide a plausible prediction for large-scale (e.g., 4096 colors) human color representation, which has yet to be fully measured empirically.

## Methodological Grounding
The alignment is quantified using [[Gromov-Wasserstein Optimal Transport (GWOT)]], a rigorous unsupervised method for comparing the geometry of disparate representational spaces without requiring predefined anchors or correspondence.

---
**Source:** [[Systematic comparison of color representations between humans and deep neural networks (2026)]]
**Clusters:** [[Neural Manifolds]], [[Linear Algebra of Subjective Experience]]

## Why it matters
Restructured during 2026-07-04 migration to Zettelkasten format.

## Connections
- Migrated from raw/color-representation-alignment-dnn.md

## Open questions
- Needs deeper linking to the new slip-box structure.

## Source
raw/color-representation-alignment-dnn.md
