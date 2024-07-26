# Knowledge Distillation and Zero-Shot Knowledge Distillation

## Overview

This repository contains implementations of knowledge distillation techniques, focusing on the paper *"Zero-Shot Knowledge Distillation in Deep Networks"* by Prof. K.R. Mopuri from IIT Hyderabad. The project aims to explore the application of knowledge distillation and zero-shot knowledge distillation using the MNIST dataset.

## Project Highlights

- **Teacher Model**: A neural network model trained on the MNIST dataset to act as a teacher model.
- **Student Model**: A smaller neural network model trained using knowledge distillation methods to approximate the performance of the teacher model.
- **Knowledge Distillation Loss**: A custom loss function combining KL divergence and cross-entropy loss, inspired by the zero-shot distillation approach.

## Contents

- **`Zero-Shot Knowledge Distillation in Deep Networks_k_r_mopuri.pdf`**: Its the inspiring research paper of Prof . K R Mopuri which we are trying to implement.
- **`Knowledge_distillation_proper.ipynb`**: Contains the model and experemental results on MNIST dataset.
- **`ZERO-Shot-knowledge-distillation notes.docx`**: Contains my personal short Notes of the research Paper.
- **`README.md`**: This file.

## Installation

To run the code, ensure you have Python 3.x installed and the required libraries:

- TensorFlow
- NumPy
- Matplotlib

## FutureWork

Future improvements include:

- Experimenting with different datasets and model architectures.
- Implementing and evaluating the zero-shot knowledge distillation as described in the paper.

## Acknowledgements

- Thanks to Prof. K R Mopuri for the innovative research on Zero-Shot Knowledge Distillation.
- Inspired by Andrew Ng’s machine learning courses.
  
