# Cohort-Amortized Personalization (CAP)

**Cohort-Amortized Personalization (CAP)** is a framework for personalizing generative brain models that replaces raw neuroimaging data sharing with model sharing. Instead of fitting models per-subject, which is computationally expensive and poses privacy risks, CAP uses a **neural density estimator** trained on simulations from a mechanistic whole-brain model under a low-rank cohort prior.

### Mechanism
- **Training**: The estimator learns to map individual data (e.g., neuroimaging) to model parameters by leveraging a prior derived from a cohort.
- **Speed**: Personalization is achieved in seconds on local data, compared to hours for traditional fitting.
- **Privacy**: Only the compact estimator (the "artifact") is distributed, preserving individual data privacy and navigating the [[virtual-brain-twins-privacy-utility|privacy-utility frontier]].

### Clinical Impact
In clinical cohorts, CAP has shown performance matching or exceeding per-subject inference for:
- **Epilepsy**: Localizing the epileptogenic zone (F1=0.56).
- **Aging**: Predicting age from brain dynamics (r=0.44).

CAP enables "synthetic access" to cohorts through [[synthetic-access-mechanistic-surrogates|mechanistic surrogates]].

[[esmaeili_cap_brain_twins_2026]]
