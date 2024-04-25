# Viscous Burgers' Equation using PINNs Model Execution Steps

## Introduction
This guide outlines the steps to execute the Physics-Informed Neural Network (PINN) for solving the viscous Burgers' Equation, which is a fundamental model in fluid mechanics.

## Dataset
The required data file "burgers_shock_mu_01_pi.mat" is included in the Data/ directory of this repository.

## Running the Model
Execute the main script or Jupyter notebook containing the model code to begin the training process. The PINN will output its accuracy and visual results upon completion.

## Visualizations
The plots generated during execution will be saved as:

- "Burgers.png" for solution visualization
- "collocation_points_Burgers.png" for collocation point distribution
  
## Evaluation
The model's performance is assessed upon completion of training, with the test error printed as a measure of accuracy.


## Support
For any issues encountered during execution, please reach out via email at: tmalepati@crimson.ua.edu

## Requirements
Before starting, ensure you have the following prerequisites:
- Python 3.7 or higher
- TensorFlow 2.x
- NumPy, Matplotlib, Scipy, pyDOE

You can install the dependencies using the following command:
```bash
pip install tensorflow numpy matplotlib scipy pyDOE






