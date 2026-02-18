# Static Structural Analysis of an Aircraft Fuselage Section

## Overview

This project presents a static finite element assessment of a representative semi monocoque aircraft fuselage section using Abaqus. The objective was to evaluate structural response under internal pressure loading and to understand load transfer through skin, frames and stringers.

The work focuses on modelling discipline, stress interpretation and validation of results against classical analytical theory.

---

## Structural Model

A detailed finite element model was developed including:

- Fuselage skin modelled using shell elements  
- Circumferential frames  
- Longitudinal stringers  
- Floor support structure  

Material properties and thickness definitions were assigned to represent a typical metallic fuselage configuration.

Boundary conditions were applied to represent constrained fuselage behaviour under distributed internal pressure loading.

---

## Analysis Approach

The assessment was performed as a linear static analysis.

Key steps included:

- Definition of representative internal pressure load case  
- Application of structural boundary conditions  
- Systematic mesh refinement study to assess stress convergence  
- Evaluation of deformation patterns and load paths  
- Identification of peak stress regions  

Mesh density was increased in stages to ensure stable and consistent stress predictions.

---

## Validation

Hoop and longitudinal stresses were compared against analytical thin cylinder theory to assess modelling accuracy.

The finite element results showed close agreement with theoretical predictions, providing confidence in the modelling assumptions and boundary condition strategy.

---

## Key Findings

- Clear load transfer from skin into frames and stringers  
- Peak stresses located at frame intersections and geometric transitions  
- Converged stress results across refined meshes  
- Structural response consistent with expected fuselage behaviour  

---

## Representative Result

<p align="center">
  <img src="fuselage_stress_contour.png" width="700">
</p>

**Figure 1:** Von Mises stress distribution under internal pressure loading. Peak stresses occur at frame and stiffener intersections, consistent with semi monocoque load transfer behaviour.

---

## Tools Used

- Abaqus  
- Linear static finite element analysis  

---

## Competencies Demonstrated

- Aircraft structural modelling  
- Load case implementation  
- Mesh convergence assessment  
- Stress interpretation  
- Structural validation against analytical theory  
- Clear and structured engineering documentation  
