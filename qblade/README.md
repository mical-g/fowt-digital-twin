# QBlade Directory

This folder houses simulation configuration files, polar data, and baseline verification results from the QBlade aeroelastic environment (Deliverable A.3).

## Simulation Setup
* **Aerodynamic Model:** Blade Element Momentum (BEM) theory.
* **Corrections Enabled:** Prandtl tip-loss factor and Glauert correction for high induction states.
* **Platform Dynamics:** Simplified platform motion simulating floating platform pitch and heave.

## Baseline Verification Target
* Baseline verification case tested at $U_\infty = 15.0 \text{ m/s}$, $\theta_{pitch} = 6.5^\circ$, and $\lambda = 6.0$.
* Required target: Power coefficient $C_P$ must fall within 5% of the NREL published value ($C_P \approx 0.48$ at rated wind speed) before sweeping parameters.