# Image Classification with Keras

## Project Overview

This project explores image classification using Convolutional Neural Networks (CNNs) implemented with the Keras API. It focuses on the CIFAR-10 dataset, demonstrating the process of building, training, and optimizing CNN models for multi-class image classification.

## Key Features

- Utilizes the CIFAR-10 dataset (60,000 32x32 color images in 10 classes)
- Implements and compares multiple CNN architectures
- Explores the impact of various hyperparameters on model performance
- Provides insights into preprocessing techniques like image normalization and one-hot encoding

## Models Implemented

1. Base Model: Initial CNN architecture
2. Model with Increased Filter Sizes
3. Model with Adjusted Dropout Rates
4. Model using RMSprop Optimizer

## Technologies Used

- Python
- Keras (with TensorFlow backend)
- NumPy
- Matplotlib

## Getting Started

1. Ensure you have Python installed on your system.
2. Install required libraries:
   ```
   pip install tensorflow numpy matplotlib
   ```
3. Clone this repository:
   ```
   git clone [repository-url]
   ```
4. Navigate to the project directory and run the main script.

## Project Structure

- `main.py`: Main script for model training and evaluation
- `models/`: Directory containing different CNN model architectures
- `utils/`: Utility functions for data preprocessing and visualization

## Results

The project demonstrates the impact of various architectural choices and hyperparameters on model performance. The best-performing model achieved [insert accuracy] accuracy on the test set.

## Future Work

- Experiment with more advanced architectures (e.g., ResNet, DenseNet)
- Implement data augmentation techniques
- Explore transfer learning using pre-trained models

## Contributors

- Fahd Azouz
- Fatima Zahra Iguenfer

## Acknowledgements

This project was supervised by Dr. Tajjedine Rachidi.
