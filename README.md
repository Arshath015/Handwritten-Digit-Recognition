# Handwritten Digit Recognition

This project demonstrates the use of machine learning for handwritten digit recognition using the Random Forest Classifier. The project is built with Python and leverages the scikit-learn library to load, visualize, and classify digits from the well-known 'digits' dataset.

## Project Overview

The main objectives of this project are:
- To load and preprocess the digit images from the dataset.
- To visualize the digit images with their corresponding labels.
- To train a Random Forest Classifier on a subset of the dataset.
- To evaluate the model's performance on a validation set.

## How It Works

1. **Dataset**: The project uses the `digits` dataset from scikit-learn, which consists of 8x8 pixel images of handwritten digits (0-9).
2. **Visualization**: The digit images are visualized using matplotlib to give an insight into the data and the associated labels.
3. **Model Training**: A Random Forest Classifier is trained using a randomly selected subset of the dataset (20% for training and 80% for validation).
4. **Evaluation**: The model's accuracy is evaluated on the validation set, and predictions are visualized to showcase the model's capabilities.

## Dependencies

- Python 3.x
- scikit-learn
- matplotlib
- numpy

Install the dependencies using pip:

```bash
pip install scikit-learn matplotlib numpy

