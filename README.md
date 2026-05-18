# Turbocharger System Design and Analysis

## Overview
This project focuses on the parametric design and engineering analysis of a turbocharger subsystem, with emphasis on centrifugal compressor geometry, volute airflow routing, housing integration, and preliminary structural validation. The project is being developed in SolidWorks using iterative CAD refinement, engineering-based design decisions, and simulation-driven evaluation.

![Turbocharger Assembly](Turbocharger%20asm%20draft.png)

---

## Objectives

- Design a realistic turbocharger compressor-side assembly
- Develop a centrifugal compressor wheel with curved blade geometry
- Create a functional volute housing with tangential outlet routing
- Improve internal airflow continuity through iterative geometry refinement
- Apply parametric CAD modeling and assembly practices in SolidWorks
- Conduct preliminary structural validation using FEA
- Document design progression, assumptions, and engineering trade-offs

---

## System Components

- Compressor Housing (Volute)
- Compressor Wheel (Impeller)
- Endplate / Mounting Structure
- Tangential Outlet Geometry
- Internal Airflow Passage

---

## Design Methodology

### 1. Research and Design Planning

- Reviewed centrifugal compressor and volute design principles
- Studied compressor airflow behavior and flow accumulation within volutes
- Referenced real turbocharger geometries, cutaways, and compressor housings
- Researched tongue/cutwater geometry and tangential outlet transitions

---

### 2. Compressor Wheel Development

- Developed initial compressor wheel geometry using revolve-based hub profiles
- Implemented curved blade geometry using lofts between sketches with spline guide curves
- Applied 12-blade circular pattern with consistent 3 mm blade thickness
- Refined blade curvature and blade spacing to better represent centrifugal airflow behavior
- Integrated compressor wheel into preliminary assembly configurations

---

### 3. Volute and Housing Development

- Designed preliminary volute housing geometry with tangential outlet integration
- Performed multiple redesign iterations of the volute to improve airflow routing and internal flow continuity
- Experimented with outlet placement, tongue/cutwater geometry, and airflow transition strategies
- Refined housing smoothness and transition regions using loft and fillet modifications
- Developed internal airflow path from compressor discharge region to outlet
- Modeled endplate and housing assembly with integrated bolt pattern geometry

#### Initial Volute Draft
![Volute Progress](Volute%20progress.png)

#### Volute With Fillet Refinement
![Volute Fillet Refinement](Volute%20with%20fillets%20applied%20for%20smoother%20cornering.png)

#### Circular Airflow Path Development
![Circular Airflow](Circular%20airflow%20in%20volute.png)

#### Endplate and Housing Geometry
![Endplate and Housing](Endplate%20and%20housing%20part.png)

#### Rear Housing View
![Rear Housing View](endplate%20and%20housing%20rear%20view.png)

---

## Assembly Development

- Integrated compressor wheel and housing geometry into an early-stage turbocharger assembly
- Refined component alignment and internal packaging
- Evaluated preliminary clearances between rotating and stationary geometry

#### Assembly Progress
![Assembly Progress](Housing%20and%20compressor%20assembly%20progress.png)

#### Turbocharger Assembly Draft
![Turbocharger Assembly](Turbocharger%20asm%20draft.png)

---

## Engineering Considerations

- Internal airflow continuity and smooth transition regions
- Tangential outlet alignment for improved flow discharge
- Structural integrity of compressor-side housing geometry
- Manufacturability of volute and housing features
- Simplified aerodynamic representation of compressor wheel geometry
- Packaging and assembly integration between wheel and housing


---
## Technical Drawing Documentation


## Compressor Wheel Technical Drawing Documentation

Created a detailed engineering drawing package for the centrifugal compressor wheel using SolidWorks drafting tools. The drawing package includes orthographic projections, an isometric reference view, and a sectional view used to communicate internal hub geometry and blade configuration.

### Compressor Wheel Technical Drawing
![Compressor Wheel Drawing](Compressor_Drawing.png)

### Drawing Features
- Orthographic front and profile views
- Section B-B view exposing internal hub geometry
- Isometric reference visualization
- Dimensional annotations for overall wheel geometry and shaft bore features
- Primary and splitter blade configuration labeling
- Rotational direction callouts
- Material specification and title block formatting
- Drafted using SolidWorks drawing environment

### Engineering Notes
- Dimensions documented in millimeters
- Section view used to communicate internal manufacturable geometry
- Drawing layout follows standard mechanical drafting workflow
- Compressor wheel modeled for conceptual turbocharger airflow analysis and assembly integration

---

Created a detailed engineering drawing package for the compressor housing endplate using SolidWorks drafting tools. The drawing package includes orthographic projections, section views, dimensional annotations, and manufacturing-oriented documentation practices.

### Compressor Housing Endplate Technical Drawing

![Compressor Housing Drawing](Compressor_Housing_Drawing.png)

### Drawing Features
- Orthographic front and profile views
- Section A-A view exposing internal geometry and wall thickness
- Isometric reference visualization
- Fully dimensioned flange and bore geometry
- Bolt pattern callouts and centerline annotations
- Fillet and feature dimensioning
- Material specification and title block formatting
- Drafted using SolidWorks drawing environment

### Engineering Notes
- Dimensions documented in millimeters
- Section view used to communicate manufacturable internal geometry
- Drawing layout follows standard mechanical drafting workflow
- Component intended for conceptual turbocharger compressor housing assembly integration

---

## Materials

### Compressor Wheel
- Material: 7075-T6 Aluminum
- Selected for lightweight high-strength rotational application assumptions

### Compressor Housing
- Material: 6061-T4 Aluminum
- Selected for structural evaluation and manufacturability considerations

### Volute
- Material: 6061-T4 Aluminum
- Selected due to its lightweight structure, manufacturability, corrosion resistance, and sufficient strength for preliminary pressure-loading analysis
---

## Compressor Housing Structural Analysis

- Conducted preliminary static structural FEA using internal pressure loading conditions
- Applied simplified internal pressure assumptions to compressor housing geometry
- Evaluated von Mises stress distribution and displacement behavior under simulated boost pressure loading
- Verified simulated stress levels remained significantly below material yield strength during initial validation testing

### Von Mises Stress Distribution on compressor housing
![Stress Distribution](stress_distribution.png)

### Stress Scale and Material Yield Comparison of compressor housing
![Stress Scale](Stress_distribution_analysis.png)

### Analysis Notes

- Maximum simulated von Mises stress reached approximately 1.51 × 10^6 Pa under applied internal pressure loading conditions
- Assigned 6061-T4 aluminum housing material has an approximate yield strength of 2.275 × 10^8 Pa
- Simulated stress levels remained substantially below material yield strength, indicating that the housing did not approach yielding under the simplified loading case
- Highest stress concentrations occurred near constrained flange transition regions while remaining within acceptable structural limits
- Preliminary results indicate acceptable structural integrity and deformation behavior for the current compressor housing design iteration

---


### Volute Structural Analysis
- Conducted preliminary structural FEA on the compressor volute housing under simplified internal pressure loading conditions
- Applied internal pressure loads to airflow-contact surfaces while constraining the lower mounting region of the volute
- Evaluated stress concentration behavior near the tongue/cutwater transition and outlet integration geometry
- Observed localized stress increases near internal transition regions while remaining below material yield strength limits


### Von Mises Stress Distribution on volute
![Stress Distribution](Stress_dist_vol.png)


### Stress Scale and Material Yield Comparison of compressor housing
![Stress Scale](Vol_von_scale.png)

### Volute Analysis Notes

- Maximum stress concentrations occurred near the tongue transition and outlet merge regions due to localized geometric discontinuities
- Structural response remained within acceptable limits under simplified boost pressure assumptions
- Results indicated improved understanding of stress behavior within asymmetric volute geometry compared to earlier simplified housing analysis
- Selected 6061-T4 aluminum provided acceptable structural performance for preliminary compressor-side loading evaluation


---


#### Structural Housing Geometry
![Volute Structural View](Volute%20structural%20top%20view.png)

---

## Key Assumptions

- Steady-state airflow conditions
- Simplified impeller aerodynamic behavior
- Uniform material properties
- Simplified static pressure loading
- No transient thermal effects in current iteration

---

## Current Limitations

- Full CFD airflow simulation not yet implemented
- Rotating impeller physics not yet modeled
- Thermal loading between turbine and compressor regions not yet analyzed
- Volute geometry still undergoing optimization and refinement

---

## Future Work

- Internal CFD flow simulation and velocity visualization
- Rotating compressor wheel analysis
- Thermal analysis across compressor and turbine regions
- Improved tongue/cutwater geometry refinement
- Optimization of volute cross-sectional area growth
- Additional assembly detailing and mounting integration

---

## Tools and Software

- SolidWorks (CAD Modeling and Assembly)
- SolidWorks Simulation (Structural FEA)
- Excel / Python (Engineering calculations and data tracking)
README.md
LICENSE
```
