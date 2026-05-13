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

- Developed initial compressor wheel geometry using revolve-based profiles
- Implemented curved blade geometry using lofts between sketches with spline guide curves
- Applied 12-blade circular pattern with consistent 3 mm blade thickness
- Refined blade curvature and spacing to better represent centrifugal airflow behavior
- Performed multiple volute redesign iterations to improve airflow routing and outlet integration
- Experimented with different tongue/cutwater geometries and internal flow passage transitions
- Refined volute smoothness and housing transitions using loft and fillet modifications
- Designed compressor housing and endplate assembly with integrated bolt pattern layout
- Integrated compressor wheel and volute housing into an early-stage turbocharger assembly
- Assigned 7075-T6 aluminum material to the compressor wheel for realistic lightweight rotational application assumptions
- Assigned 6061-T4 aluminum material to the compressor housing for structural and manufacturability evaluation
- Conducted preliminary static structural FEA using internal pressure loading conditions
- Evaluated von Mises stress distribution and displacement behavior under simplified boost pressure assumptions
- Verified simulated stress levels remained below material yield strength during initial validation testing
  
---

## Repository Structure
