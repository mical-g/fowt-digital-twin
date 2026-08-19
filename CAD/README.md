# CAD Directory

This folder stores the 3D parametric computer-aided design (CAD) files for the NREL 5 MW reference wind turbine blade (Deliverables A.1 and A.2).

## Contents
* `nrel_5mw_blade.ipt`: Parametric 3D solid model built in Autodesk Inventor.
* `nrel_5mw_blade.step`: Standard neutral format export for cross-platform portability.

## Modelling Approach & Assumptions
* Geometry Source: Extracted from 19 spanwise stations defined in Jonkman et al. (2009), tracking chord length c(r), twist angle beta(r) and S-series aerofoil profiles (S818, S825, S826).
* Loft Strategy: 2D profiles imported from UIUC coordinates, placed at correct spanwise intervals, scaled by chord, rotated by twist, and interpolated via Inventor's Loft tool.
* Material Property: Assigned Structural Steel (E = 200 GPa}, sigma_y = 250 MPa, rho = 7850 kg/m^3) for consistency with the data contract and FEA validation, noting that real blades are glass-fibre composite.