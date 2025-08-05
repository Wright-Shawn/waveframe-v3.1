# 06 – Model Validation Results

This document addresses a key critique from external review: the absence of explicit validation metrics and observational residuals in Waveframe v3.1. The goal is to present numerical evidence comparing the Waveframe model to standard cosmological datasets, providing residuals, goodness-of-fit scores, and benchmark metrics.

## Validation Strategy

We assess the model against three major observational axes:

- The Hubble expansion rate                             H(z)
- The luminosity distance-redshift relation                    d_L(z)
- The structure growth rate inferred from redshift space distortions fσ₈(z)

All comparisons are conducted using numerical integrations of the Waveframe expansion law:

     Ḣ(t) = −[γ(z) · H³(t)] ⁄ 2π

with corresponding definitions for entropy-based observables:

     S(t) = π ⁄ H²(t)  
     d_C(z) = ∫₀ᶻ [c ⁄ H(z′)] dz′  
     d_L(z) = (1 + z) · d_C(z)

Growth predictions are generated via a perturbation equation:

     f(z) = dlnD ⁄ dlna  
     fσ₈(z) = f(z) · σ₈(z)

where D is the linear growth factor solved via a modified second-order ODE using H(z) from the entropy law.

## Residuals vs Observations

All results and figures are produced in the notebook:
