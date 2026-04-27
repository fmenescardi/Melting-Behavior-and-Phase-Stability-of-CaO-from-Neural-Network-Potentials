This directory contains representative PANNA input files used to train and validate the MLIP described in the paper.

The files define:
- neural network architecture
- descriptor (LATTE)
- training parameters

The full dataset (training, validation, and test configurations) is available at:
https://doi.org/10.5281/zenodo.19814455

panna_train.ini is the input to train the neural network on the given dataset. 
panna_val.ini is the input to validate the network on a given test set 
panna_extract_weights.ini is the input to extract weights from the trained network and produce the potential then employed in LAMMPS MD calculations. 
