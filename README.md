
# Scuba Diving Ballast Optimization

### A Mathematical Modeling Approach to Determining the Minimum Feasible Ballast Weight

## Project Overview

This project develops a mathematical framework to determine the theoretical minimum feasible ballast weight for a recreational scuba diver.

Using principles from fluid mechanics, numerical modeling, and constrained optimization, the project investigates how buoyancy changes throughout a dive and how different equipment configurations and environmental conditions affect ballast requirements.

The analysis is divided into four stages.

## Methodology

### Stage 1: Static Buoyancy Model
- Apply Archimedes' principle to calculate the buoyant forces acting on a diver and their equipment.
- Establish a baseline neutral-buoyancy model under fixed conditions.

### Stage 2: Dynamic Buoyancy Model
- Model time-dependent cylinder gas consumption.
- Investigate depth-dependent wetsuit compression using two buoyancy models.
- Incorporate adjustable BCD buoyancy and its constraints.

### Stage 3: Constrained Optimization
- Formulate the minimum ballast weight problem as a constrained optimization problem.
- Use Python-based numerical evaluation to determine the feasible ballast interval.
- Verify whether BCD adjustment remains within the assumed limits throughout the dive.

### Stage 4: Sensitivity Analysis
Evaluate the effects of:
- Wetsuit thickness and compression
- Cylinder configuration and respiratory minute volume
- BCD characteristics
- Diver body mass and density
- Seawater and freshwater density
- Dive depth and duration

## Key Results

For the reference 50-minute dive scenario:

| Metric | Result |
|---|---|
| Minimum feasible ballast | 12.46 kg |
| Feasible ballast interval | 12.46–18.23 kg |
| Maximum required additional BCD buoyancy | 85.61 N |
| Predicted final cylinder pressure | 1013 psi |

The sensitivity analysis indicates that wetsuit configuration, water density, and body density substantially influence theoretical ballast requirements.

Wetsuit compression and dive depth are particularly important for determining the additional buoyancy required from the BCD.

## Mathematical & Computational Methods

- Archimedes' Principle
- Hydrostatic Pressure and Boyle's Law
- Dynamic Mathematical Modeling
- Numerical Integration
- Constrained Optimization
- Sensitivity Analysis
- Python-Based Numerical Evaluation

## Limitations

The model is based on simplified assumptions and published reference data rather than diver-specific measurements. It does not establish operational dive safety or provide validated weighting recommendations.

## Full Report

The complete report includes mathematical derivations, numerical simulations, sensitivity analysis, figures, and references.

## Author

Yingchen Lin
