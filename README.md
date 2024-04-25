# lottery-ticket-hypothesis-under-structured-pruning
## Overview
This repository contains the implementation of the Lottery Ticket Hypothesis (LTH) under structured pruning, an approach for neural network compression. The Lottery Ticket Hypothesis suggests that a sparse subnetwork, called a "winning ticket," exists within a larger dense neural network and can be trained in isolation to achieve comparable performance.

In this project, we explore the application of the Lottery Ticket Hypothesis in the context of structured pruning, where entire channels or filters are pruned from convolutional layers. We investigate how the LTH performs under different pruning strategies and analyze its effectiveness in reducing model size while preserving accuracy.

## Requirements
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## Usage
1. Clone the repository
2. Navigate to the project directory:
3. Run the experiments: python main.py
This will train the neural network, apply structured pruning, and evaluate the performance of the pruned model.

## result
We provide experimental results and analysis in the results directory. You can find detailed reports, including accuracy plots, training curves, and comparisons between the original and pruned models.

## Contributing
Contributions to this project are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request.
