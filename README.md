# Viscous Burgers' Equation using PINNs Model Execution steps.

## Introduction
This guide provides quick steps to run the Physics-Informed Neural Network (PINN) for solving the viscous Burgers' Equation, a key model in fluid mechanics.

## Requirements
- Python 3.7+
- TensorFlow 2.x
- NumPy, Matplotlib, Scipy, pyDOE

Install dependencies using:
```bash
pip install tensorflow numpy matplotlib scipy pyDOE


## Dataset
The required data file `burgers_shock_mu_01_pi.mat` should be placed in the `Data/` directory of the project, which i have uploaded in this repo.

## Running the Model
To run the model, execute the main script or Jupyter notebook containing the model code. The training process of the PINN will be carried out, and it will output the model's accuracy along with visual results.

## Visualizations
The resulting plots will be saved as `Burgers.png` for the solution visualization and `collocation_points_Burgers.png` for visualizing the distribution of collocation points.

## Evaluation
After the training is complete, the model's performance will be evaluated and the test error will be printed as an accuracy measure.

## Issues
If you encounter any issues,  email to : tmalepati@crimson.ua.edu
