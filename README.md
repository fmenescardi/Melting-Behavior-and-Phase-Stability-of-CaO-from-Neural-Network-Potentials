# Melting Behavior and Phase Stability of CaO from Neural Network Potentials

This repository contains the potential files, and computational scripts associated with the study of Calcium Oxide (CaO) phase stability and melting behavior under extreme conditions.

## Data Availability
The full dataset supporting this work is available at Zenodo: https://doi.org/10.5281/zenodo.19814455

## Project Overview
This research utilizes a **Machine Learning Interatomic Potential (MLIP)** to investigate the melting temperature ($T_m$) of CaO. The potential was developed using the **PANNA 2.0** framework with the **LATTE** descriptor and trained on a diverse dataset of approximately 12,000 configurations.

## Repository Content
This repository includes:

*   **Neural Network Potential**: Parameters for the multilayer perceptron (MLP) architecture used in the simulations.
*   **Input Scripts**:
    *   **Quantum ESPRESSO (v6.8)**: Inputs for DFT/PBEsol reference data generation.
    *   **PANNA 2.0**: Configuration files for potential training.
    *   **LAMMPS**: Scripts for Void-Nucleated Melting (VNM) and Two-Phase Coexistence (TPC) simulations.
*   **Trajectories**: Initial configurations for the MD simulations.

## Software Requirements
*   **Quantum ESPRESSO**: For first-principles calculations.
*   **PANNA 2.0**: For neural network potential generation and training.
*   **LAMMPS**: For large-scale molecular dynamics production runs.

## Citation
If you use these materials, please cite the following work:
> Menescardi, F., & de Gironcoli, S. "Melting Behavior and Phase Stability of CaO from Neural Network Potentials: a Molecular Dynamics Study" (2026).

--------------------------------------------------------------------------------
