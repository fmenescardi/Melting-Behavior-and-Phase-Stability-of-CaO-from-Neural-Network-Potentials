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
    *   **Quantum ESPRESSO (v6.8)**: Inputs for DFT/PBEsol reference data generation and AIMD simulations.
    *   **PANNA 2.0**: Inputs for training and validation of the network and weights extraction.
    *   **LAMMPS**: Scripts for Void-Nucleated Melting (VNM) and Two-Phase Coexistence (TPC) simulations.

## Software Requirements
The simulations and data generation in this work were performed using the following software:

- **Quantum ESPRESSO (v6.8)**  
  For first-principles (DFT) calculations.  
  Giannozzi et al., J. Phys.: Condens. Matter 21, 395502 (2009)  
  https://doi.org/10.1088/0953-8984/21/39/395502  

- **PANNA 2.0**  
  For neural network potential training and inference.  
  Pellegrini et al., J. Chem. Phys. 159 (2023)  
  https://doi.org/10.1063/5.0155182
  https://arxiv.org/abs/2405.08137 

- **LAMMPS**  
  For large-scale molecular dynamics simulations.  
  Thompson et al., Comput. Phys. Commun. 271, 108171 (2022)  
  https://doi.org/10.1016/j.cpc.2021.108171

## Citation
If you use these materials, please cite the following work:
> Menescardi, F., & de Gironcoli, S. "Melting Behavior and Phase Stability of CaO from Neural Network Potentials: a Molecular Dynamics Study" (2026).

--------------------------------------------------------------------------------
