---
id: 2026-07-04 11:01:32
title: Esmaeili Cap Brain Twins 2026
topic: neuroscience
type: permanent
source: Internal Migration
tags: []
created: 2026-07-04
---

## Idea
# Cohort-Amortized Personalization: Virtual Brain Twins (Esmaeili et al., 2026)

**Title:** Cohort-amortized personalization: navigating the privacy-utility frontier for virtual brain twins
**Authors:** Amirhossein Esmaeili, et al.
**arXiv:** [[2606.30329]]
**Date:** June 2026

### Overview
This paper introduces **Cohort-Amortized Personalization (CAP)**, a method to create [[virtual-brain-twins-privacy-utility|Virtual Brain Twins]] without the need for sharing raw neuroimaging data. CAP utilizes a neural density estimator and a [[crosscoder-atlas-independent-personalization|CrossCoder]] autoencoder to enable fast, private, and atlas-independent personalization.

### Key Innovations
- **CAP Framework**: Replaces per-subject fitting with a shared density estimator trained on a low-rank cohort prior. See [[cohort-amortized-personalization-cap]].
- **CrossCoder**: A cross-atlas autoencoder that provides an atlas-independent latent space for connectomes. See [[crosscoder-atlas-independent-personalization]].
- **Synthetic Access**: A new paradigm for data sharing that provides mechanistic surrogates for experimentation instead of raw data. See [[synthetic-access-mechanistic-surrogates]].

### Clinical Validation
- **Epilepsy Localization**: Achieved F1=0.56 in epileptogenic-zone localization across 21 patients.
- **Aging Research**: Predicted age with r=0.44 in a cohort of 832 subjects (1000BRAINS).
- **Efficiency**: Reduced personalization time from hours to seconds.

### Significance
CAP addresses the major bottlenecks in clinical translation of personalized brain models: privacy, compute time, and site heterogeneity. By moving toward model-sharing and synthetic access, it facilitates large-scale multi-site neuroimaging research.

## Why it matters
Restructured during 2026-07-04 migration to Zettelkasten format.

## Connections
- Migrated from biology/neuroscience/computation/esmaeili_cap_brain_twins_2026.md

## Open questions
- Needs deeper linking to the new slip-box structure.

## Source
biology/neuroscience/computation/esmaeili_cap_brain_twins_2026.md
