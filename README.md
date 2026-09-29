# ANN-Iris-Flower-Classification
Iris flower classification using an Artificial Neural Network (ANN) with TensorFlow/Keras for multi-class classification.
# ANN Iris Flower Classification

This project uses an Artificial Neural Network (ANN) built with TensorFlow/Keras to classify Iris flowers into three different species based on their sepal and petal measurements.

## Project Overview

The Iris dataset contains measurements of Iris flowers, including:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The objective of this project is to train an Artificial Neural Network to classify each flower into one of three species:

- Setosa
- Versicolor
- Virginica

This project demonstrates the basic workflow of building and training an ANN for a multi-class classification problem.

## Dataset

The project uses the Iris dataset containing:

- 150 samples
- 4 input features
- 3 target classes

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |

### Target

The target variable is `species`.

The categorical species labels are converted into numerical labels:

```text
Setosa      → 0
Versicolor  → 1
Virginica   → 2
