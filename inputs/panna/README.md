# PANNA Input Files

This directory contains representative input files used to train and validate the Machine Learning Interatomic Potential (MLIP) for CaO, as described in the associated study.

## Overview

The MLIP is trained using the PANNA framework with the LATTE descriptor.  
The files provided here define the neural network architecture, descriptor settings, and training/validation workflow.

These inputs are intended to document the training procedure and ensure reproducibility of the model generation process.

## Contents

- panna_train.ini  
  Training configuration file defining:
  - neural network architecture (e.g. 256:124:1)
  - training hyperparameters (learning rate schedule, epochs)
  - dataset references

- panna_val.ini  
  Validation configuration file used to monitor model performance during training.

- panna_extract_weights.ini  
  Configuration used to extract the trained model weights for use in LAMMPS.

## Dataset

The full dataset used for training, validation, and testing (including atomic configurations, energies, forces, and stress tensors) is available at: https://doi.org/10.5281/zenodo.19814455

Paths in the input files referring to training data are illustrative and may need to be adapted to local environments.

## Notes

- These files are representative of the training setup and are not intended to be run directly without the corresponding dataset.
- The dataset is not included in this repository due to size constraints and is archived on Zenodo.
- File paths have been simplified for portability.
