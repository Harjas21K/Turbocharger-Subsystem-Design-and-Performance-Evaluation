# Turbocharger System Design and Analysis

## Overview
This project focuses on the parametric design and engineering analysis of a turbocharger system, with emphasis on centrifugal compressor volute geometry, airflow management, and thermal considerations. The goal is to develop a mechanically and thermodynamically consistent design using SolidWorks, supported by research-driven decisions and iterative refinement.

---

## Objectives
- Design a realistic turbocharger assembly (compressor, turbine, shaft, intercooler)
- Develop a compressor volute with proper cross-sectional area distribution
- Incorporate thermal-aware design between turbine and compressor regions
- Apply parametric CAD modeling techniques in SolidWorks
- Document engineering assumptions, design rationale, and trade-offs

---

## System Components
- Compressor Housing (Volute)
- Compressor Wheel (Impeller)
- Turbine Housing
- Shaft Assembly
- Intercooler and Piping
- Mounting and Structural Components

---

## Design Methodology

### 1. Research
- Reviewed centrifugal compressor and volute design principles
- Analyzed cross-sectional area distribution and flow behavior
- Studied real turbocharger geometries and cutaway models

### 2. Concept Development
- Defined baseline dimensions using proportional scaling
- Established inlet diameter as primary reference parameter
- Developed initial volute geometry based on gradual area expansion

### 3. CAD Modeling (SolidWorks)
- Parametric modeling of individual components
- Assembly creation with constraint-based alignment
- Interference detection and clearance validation

### 4. Engineering Considerations
- Flow path continuity and smooth transitions
- Thermal isolation between turbine and compressor
- Manufacturability (DFM) of housing geometries
- Structural integrity of rotating components

### 5. Analysis (Planned / In Progress)
- Thermal distribution across turbine and compressor regions
- Airflow behavior within volute geometry
- Stress and deformation under operating conditions

---

## Compressor Volute Design Notes
- Volute designed with progressively increasing cross-sectional area
- Geometry based on conservation of mass and flow accumulation
- Outlet positioned tangentially to spiral for smooth flow transition
- Emphasis on minimizing turbulence and pressure loss

---

## Key Assumptions
- Steady-state airflow conditions
- Simplified impeller geometry for initial design phase
- Uniform material properties
- Neglecting transient thermal effects (initial iteration)

---

## Tools and Software
- SolidWorks (CAD and Assembly)
- SolidWorks Simulation (Thermal / Structural)
- Excel / Python (for calculations and data tracking)

---
Developed initial compressor wheel geometry using revolve-based profile
Implemented curved blade architecture using lofts between multiple sketches with spline guide curves
Applied 12-blade circular pattern with consistent 3 mm blade thickness for geometric uniformity
Refined blade curvature, spacing, and orientation to better represent centrifugal compressor airflow behavior
Performed multiple iterative redesigns of the volute geometry to improve airflow routing, outlet transition smoothness, and overall housing integration
Experimented with different volute cross-sectional shapes, outlet positioning strategies, and tongue/cutwater transition concepts during geometry development
Reworked internal airflow passage geometry several times to improve continuity between the compressor outlet region and tangential discharge outlet
Iteratively refined volute transitions and housing geometry using fillets and loft modifications for smoother internal flow paths and reduced sharp geometric discontinuities
Designed preliminary volute housing geometry with tangential outlet integration and internal airflow pathway development
Modeled compressor housing/endplate assembly with integrated bolt pattern layout and mounting structure
Integrated compressor wheel and housing components into an early-stage turbocharger assembly configuration
Assigned 7075-T6 aluminum material to the compressor wheel for lightweight high-strength rotational application assumptions
Assigned 6061-T4 aluminum material to the compressor housing for realistic manufacturability and structural evaluation context
Conducted preliminary static structural FEA under simplified internal pressure loading conditions
Evaluated von Mises stress distribution and housing deformation behavior under applied pressure conditions
Verified simulated stress levels remained significantly below material yield strength during initial structural validation testing
---

## Repository Structure
