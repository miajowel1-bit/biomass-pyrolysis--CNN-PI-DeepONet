# biomass-pyrolysis--CNN+PI-DeepONet


This repository contains the complete code associated with the study:

****

The study presents a hybrid physics-informed machine learning framework for estimating kinetic parameters during biomass pyrolysis. The proposed framework combines a convolutional neural network (CNN) with a physics-informed deep operator network (PI-DeepONet) to estimate kinetic parameters and reconstruct biomass conversion curves.

## Methodology

The framework employs a three-pseudo-component discrete distributed activation energy model (DAEM) with first-order reaction kinetics to describe the pyrolysis process.

The inverse model consists of:

- Convolutional neural network (CNN) for kinetic parameter estimation
- Frozen physics-informed DeepONet (PI-DeepONet) for conversion-curve reconstruction
- Physics-based reconstruction loss for guiding the inverse prediction
- Three-pseudo-component DAEM for biomass pyrolysis kinetics

The framework was evaluated using experimental thermogravimetric analysis (TGA) data for:

- Date seeds
- Coconut shells

at heating rates of 5, 15, and 25 °C/min.

## Repository Contents

- CNN+PI_DeepONet.ipynb` — Complete Google Colab/Jupyter Notebook containing the model implementation, training, parameter estimation, and analysis.

## Requirements

The code was developed and tested using Python and the following major libraries:

- NumPy
- Pandas
- SciPy
- Matplotlib
- Scikit-learn
- PyTorch

Additional packages required by the notebook are specified within the code.

## Usage

The notebook can be opened directly in Google Colab or Jupyter Notebook.

To reproduce the analysis:

1. Download or clone this repository.
2. Open `biomass_pyrolysis_PI_DeepONet.ipynb`.
3. Install the required Python packages.
4. Provide the required TGA data.
5. Run the notebook cells sequentially.

## Data Availability

The experimental TGA data used in this study are not included in this repository.

## Citation

