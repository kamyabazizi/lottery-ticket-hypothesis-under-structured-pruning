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
1. Clone the repository:
  '''bash
   git clone https://github.com/kamyabazizi/lottery-ticket-hypothesis-under-structured-pruning.git'''
2.   
