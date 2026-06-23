# ANSYS Taylor Test - Cylinder Impact Analysis

## Project Overview

This project simulates a Taylor Impact Test using ANSYS Explicit Dynamics. An aluminum alloy cylinder impacts a fixed structural steel plate at high velocity to study plastic deformation behavior and energy transfer during impact.

The analysis is commonly used to validate material models under high strain-rate loading conditions.

## Problem Statement

Perform the impact analysis of a cylindrical projectile striking a fixed steel plate.

### Input Parameters

- Initial Velocity: 100 m/s
- Projectile Material: Aluminum Alloy NL
- Target Plate Material: Structural Steel NL
- Analysis Type: Explicit Dynamics
- Contact Type: Body Interaction
- Bottom Face of Plate: Fixed Support

## Objectives

- Evaluate Equivalent Plastic Strain
- Determine Total Deformation
- Analyze Energy Absorption during Impact
- Observe High-Speed Impact Behavior

## Software Used

- ANSYS Workbench 2025 R2 Student
- Explicit Dynamics Solver (AUTODYN)

## Methodology

1. Create cylinder and plate geometry.
2. Assign nonlinear material models.
3. Define body interaction contact.
4. Apply fixed support to plate.
5. Assign initial velocity of 100 m/s to cylinder.
6. Generate structured mesh.
7. Perform explicit dynamic simulation.
8. Post-process deformation and plastic strain results.

## Results

### Total Deformation
- Maximum deformation ≈ 1.019 mm
- Progressive deformation observed during impact event.

### Equivalent Plastic Strain
- Maximum equivalent plastic strain ≈ 0.1488
- Highest plastic strain concentrated near impact interface.

### Energy Response
- Kinetic energy converted into deformation energy.
- Plastic deformation absorbed impact energy effectively.

## Files Included

- TAYLOR TEST AK.wbpj
- VID TAYLOR TEST.mp4
- Result screenshots
- Explicit Dynamics simulation files

## Applications

- Ballistic impact studies
- Crashworthiness analysis
- Material characterization
- High strain-rate deformation analysis
- Aerospace and defense engineering

## Author

AravinthKrishna G P  
M.E Engineering Design  
College of Engineering Guindy, Anna University
