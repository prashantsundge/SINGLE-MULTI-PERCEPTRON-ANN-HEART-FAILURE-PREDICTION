# Heart Failure Prediction using Artificial Neural Networks (ANN)

## Overview

This repository contains code and resources for predicting heart failure using Artificial Neural Networks (ANN). The project explores two approaches: a single perceptron ANN with GridSearchCV for hyperparameter tuning and a multi-layer perceptron (MLP) with early stopping and dropouts for regularization.

# Table of Contents

1. [Introduction](#introduction)
2. [Import Libraries](#import-libraries)
3. [Load Dataset](#load-dataset)
4. [Split the Data into X and Y](#split-the-data-into-x-and-y)
5. [Standard Scaler](#standard-scaler)
6. [Train-Test Split](#train-test-split)

## Single Perceptron (Linear Model)

7. [Single Perceptron Model Fit](#single-perceptron-model-fit)
8. [Single Perceptron Model Predict](#single-perceptron-model-predict)
9. [Single Perceptron Model Accuracy Score (68%)](#single-perceptron-model-accuracy-score-68%)

## Perceptron with GridSearchCV

10. [Perceptron with GridSearchCV Fit](#perceptron-with-gridsearchcv-fit)
11. [Perceptron with GridSearchCV Predict](#perceptron-with-gridsearchcv-predict)
12. [Perceptron with GridSearchCV Accuracy Score (69.33%)](#perceptron-with-gridsearchcv-accuracy-score-69.33)
13. [Best Perceptron Selection](#best-perceptron-selection)
14. [Best Perceptron Selection Accuracy Score (73.33%)](#best-perceptron-selection-accuracy-score-73.33)

## Early Stopping

15. [Early Stopping](#early-stopping)

## Multi-Layer Perceptron using TensorFlow and Keras

16. [Import TensorFlow and Keras Libraries](#import-tensorflow-and-keras-libraries)
17. [Sequential Model](#sequential-model)
18. [Add Dense](#add-dense)
19. [Add Dropouts](#add-dropouts)
20. [Add ReLU Activation Function](#add-relu-activation-function)
21. [Add Input Layer](#add-input-layer)
22. [Add Hidden Layer](#add-hidden-layer)
23. [Add Sigmoid Activation Function](#add-sigmoid-activation-function)
24. [Model Compile](#model-compile)
25. [Adam Optimizer](#adam-optimizer)
26. [Binary Crossentropy Loss Function](#binary-crossentropy-loss-function)
27. [Plot Model Accuracy with Epoch](#plot-model-accuracy-with-epoch)
28. [Plot Model Loss with Epoch](#plot-model-loss-with-epoch)

## Introduction

Heart failure is a critical health condition, and predicting it accurately can aid in early intervention and treatment. This project leverages Artificial Neural Networks to predict heart failure based on relevant features.

## Dataset

The dataset used in this project is [provide_dataset_name], containing [number_of_samples] samples and [number_of_features] features. For data preprocessing details, refer to [data_preprocessing_script].

## Code Structure

- `src/`: Contains the source code.
  - `single_perceptron_ann.py`: Implementation of a single perceptron ANN.
  - `grid_search_cv.py`: Hyperparameter tuning using GridSearchCV.
  - `mlp_early_stopping_dropout.py`: Implementation of a multi-layer perceptron with early stopping and dropouts.
- `data/`: Directory for storing datasets.
- `results/`: Directory for storing model evaluation results.

## Single Perceptron ANN

The `single_perceptron_ann.py` script implements a single perceptron ANN for heart failure prediction.

## GridSearchCV

The `grid_search_cv.py` script utilizes GridSearchCV for hyperparameter tuning to optimize the performance of the single perceptron ANN.

## Multi-layer Perceptron (MLP)

The `mlp_early_stopping_dropout.py` script implements a multi-layer perceptron for heart failure prediction. It incorporates early stopping and dropouts for better generalization.

## Early Stopping and Dropouts

To prevent overfitting and improve generalization, the MLP implementation uses early stopping and dropouts.

## Results

Model evaluation results, including accuracy, loss, and other metrics, can be found in the `results/` directory.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/heart-failure-prediction.git
