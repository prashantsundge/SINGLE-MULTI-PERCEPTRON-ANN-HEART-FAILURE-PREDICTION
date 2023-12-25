# Heart Failure Prediction using Artificial Neural Networks (ANN)

## Overview

This repository contains code and resources for predicting heart failure using Artificial Neural Networks (ANN). The project explores two approaches: a single perceptron ANN with GridSearchCV for hyperparameter tuning and a multi-layer perceptron (MLP) with early stopping and dropouts for regularization.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Code Structure](#code-structure)
- [Single Perceptron ANN](#single-perceptron-ann)
- [GridSearchCV](#gridsearchcv)
- [Multi-layer Perceptron (MLP)](#multi-layer-perceptron-mlp)
- [Early Stopping and Dropouts](#early-stopping-and-dropouts)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

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
