# 03. Entropy Conservation Equation

## Overview

In this section, we derive the differential form of entropy conservation in the Waveframe framework, emphasizing its role as a governing constraint rather than a passive outcome. Unlike energy conservation, which is often embedded in symmetry assumptions, entropy conservation in Waveframe arises from horizon information invariance under adiabatic expansion.

## Entropy Definition

We begin with the foundational entropy-area relation:

\[
S(t) = \frac{\pi}{H(t)^2}
\]

Taking the time derivative:

\[
\dot{S}(t) = -2\pi \cdot \frac{\dot{H}(t)}{H(t)^3}
\]

This defines the change in entropy as directly related to the acceleration of the expansion rate. However, in the absence of entropy production, we demand:

\[
\dot{S}(t) = 0
\]

Which implies:

\[
\dot{H}(t) = 0
\]

This corresponds to de Sitter equilibrium. To generalize this, we allow controlled entropy production or conservation under dynamics.

## Modified Conservation Law

Introduce an entropy flux term \( \Phi_S(t) \) to encode deviations from equilibrium:

\[
\dot{S}(t) + \Phi_S(t) = 0
\]

Substituting the definition of \( \dot{S}(t) \):

\[
-2\pi \cdot \frac{\dot{H}(t)}{H(t)^3} + \Phi_S(t) = 0
\]

Solving for \( \dot{H}(t) \):

\[
\dot{H}(t) = \frac{H(t)^3}{2\pi} \Phi_S(t)
\]

This forms the basis of entropy-modulated expansion, replacing scalar field pressure terms with informational flux.

## Physical Interpretation

- When \( \Phi_S(t) = 0 \), the universe approaches de Sitter stasis (constant Hubble rate).
- When \( \Phi_S(t) > 0 \), entropy flows out of the observable horizon (accelerating expansion).
- When \( \Phi_S(t) < 0 \), entropy accumulates inside the horizon (decelerating expansion or contraction).

In this framework, cosmic evolution is interpreted as the dynamics of entropy flow across a causal surface.

## Closing Remarks

This conservation equation will be used to constrain permissible models in the Waveframe expansion law and guide parameter fitting against observational data. It is a core pillar of the entropic formulation, linking horizon dynamics, entropy evolution, and cosmological acceleration without invoking exotic fields or dark sector speculation.
