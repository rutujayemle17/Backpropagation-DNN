# Backpropagation Algorithm Project

## Overview
This project implements a backpropagation algorithm for training a simple neural network. The backpropagation process adjusts weights based on the error computed at the output, propagating this adjustment backward through the network layers. This implementation is built with a focus on educational purposes and highlights the fundamental concepts of forward propagation, loss calculation, and gradient-based optimization.

## Project Contents
The project includes the following main features:
- A basic neural network with at least two hidden layers.
- Activation functions for non-linear transformation (e.g., sigmoid).
- Mean Squared Error (MSE) as the loss function.
- Gradient descent for updating weights.

## Requirements
To run the code, you need the following Python libraries:
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization (if visualizations are added).

You can install the dependencies using:
```bash
pip install numpy matplotlib
```

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/rutujayemle17/Backpropagation-DNN
   ```
2. Ensure that all dependencies are installed as specified in the `Requirements` section.
3. Run the Python script to execute the backpropagation training process.

## Code Explanation
### Key Components:
- **Forward Propagation**: The input data is passed through the network layers to produce an output prediction.
- **Loss Calculation**: The Mean Squared Error (MSE) between the predicted output and the target value is computed.
- **Backpropagation**: The gradients of the loss with respect to the weights are calculated using chain rule derivatives, and the weights are updated using gradient descent.

For a complete step-by-step breakdown, see the code 
