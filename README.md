# Melting Behavior and Phase Stability of CaO from Neural Network Potentials

This repository contains the datasets, potential files, and computational scripts associated with the study of Calcium Oxide (CaO) phase stability and melting behavior under extreme conditions.

## Project Overview
This research utilizes a **Machine Learning Interatomic Potential (MLIP)** to investigate the melting temperature ($T_m$) of CaO. The potential was developed using the **PANNA 2.0** framework with the **LATTE** descriptor and trained on a diverse dataset of approximately 12,000 configurations.

## Repository Content
In compliance with the transparency guidelines of *npj Computational Materials*, this repository includes:

*   **Training & Validation Datasets**: ~12,000 structural configurations in JSON format, including solid (300 K - 3200 K), liquid (2000 K - 6000 K), interfacial, void-containing, and EOS structures.
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
