# CLIP as a Proxy for Human Color Vision

## The Superiority of CLIP at High Levels
While early layers of most Deep Neural Networks (DNNs) capture low-level sensory structures like color, these representations often diverge from human perception in higher-level output layers. [[CLIP]] (Contrastive Language-Image Pre-training) is unique in its ability to sustain a color representation that geometrically aligns with human data throughout its entire architecture.

## Why CLIP?
The study suggests that training on image-text pairs (rather than images alone or image-label pairs) enables the acquisition of a color representation that is structurally congruent with human perception. This implies that language-grounded visual training better approximates the complex, multi-scale way humans represent and categorize colors.

## Predictive Power
Because CLIP aligns so well with the limited empirical data we have (e.g., 93 colors), its representational structure in larger spaces (e.g., 4096 colors) serves as a plausible prediction for human perception where psychophysical experiments are currently infeasible.

---
**Source:** [[Systematic comparison of color representations between humans and deep neural networks (2026)]]
**Clusters:** [[Neural Manifolds]], [[Linear Algebra of Subjective Experience]]
