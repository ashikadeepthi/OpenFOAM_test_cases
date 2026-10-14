
# OpenFOAM Cylinder Flow Validation Cases

This repository contains OpenFOAM test cases for stationary
and oscillating cylinder flow using overset meshes.

## Test Cases

### 1. Stationary Cylinder — Re = 100

Directory: `RE_100_stat_overset/`

Contains the OpenFOAM initial and boundary conditions,
mesh, physical properties, and numerical configuration.

### 2. Oscillating Cylinder — Re = 185

Directory: `RE_185_coarse_0.8_oscillating_cyl/`

Contains the OpenFOAM configuration and mesh for an
oscillating-cylinder simulation.

## Directory Structure

Each case includes:

- `0/`: Initial and boundary conditions
- `constant/`: Physical properties and mesh
- `system/`: Numerical schemes and solver controls

## Software

- OpenFOAM: Specify the version used

## Running the Cases

Review the dictionaries and solver settings before running.
The required solver and execution commands should be
documented for each case.

## Validation

Add comparisons against published benchmark data,
including drag coefficient, Strouhal number, and other
relevant quantities where applicable.
=======
# OpenFOAM_test_cases
>>>>>>> 16cb06a0d66906f2e6a12dc56173a57127ca0b0a
