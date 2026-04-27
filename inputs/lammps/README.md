# LAMMPS Input Files

This directory contains representative LAMMPS input files used for the molecular dynamics simulations described in the associated study on CaO melting behavior.

## Overview

The simulations are performed using a Machine Learning Interatomic Potential (MLIP) trained with the PANNA framework. All simulations employ periodic boundary conditions and are carried out using the LAMMPS package.

The input files provided here are representative examples of the workflows used in this work and are intended to ensure reproducibility of the simulation protocol.

## Contents

- TPC_01_make_interface_example.in  
  Preparation of the solid–liquid interface used in the two-phase coexistence (TPC) method.

- TPC_02_equilibrate_interface_example.in  
  Equilibration of the interface in the NPT ensemble at the estimated melting temperature.

- TPC_03_nph_production_example.in  
  Final NPH simulation used to determine the melting temperature from phase coexistence.

- VNM_example.in  
  Representative input for the void-nucleated melting (VNM) method.

- potential/  
  Directory containing the trained MLIP used in the simulations.

- start.data
  Starting unit-cell CaO configuration employed in these inputs.

## Notes

- File paths have been adapted to be portable and may require adjustment depending on the local environment.
- These inputs are intended as reference examples and may require additional files (e.g., structure or restart files) to run directly.
