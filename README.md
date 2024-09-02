# Breast Cancer Classification Project

## Overview

This project implements a machine learning model to classify breast cancer tumors as either malignant or benign based on features extracted from digitized images of fine needle aspirates (FNA) of breast masses. The model uses the Breast Cancer Wisconsin (Diagnostic) dataset and employs a Support Vector Machine (SVM) classifier for prediction.

## Table of Contents

1. [Dataset](#dataset)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model Details](#model-details)
6. [File Descriptions](#file-descriptions)
7. [Future Improvements](#future-improvements)

## Dataset

The Breast Cancer Wisconsin (Diagnostic) dataset is used in this project. It includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image.

- **Source**: UCI Machine Learning Repository
- **Features**: 30 real-valued features
- **Classes**: 2 (Malignant and Benign)
- **Samples**: 569

For more information about the dataset, visit the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).

## Requirements

- Python 3.6+
- NumPy
- scikit-learn

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Its-Anay/BreastCancer_classification.git
   cd BreastCancer_classification
   ```

2. Install the required packages:
   ```
   pip install numpy scikit-learn
   ```

## Usage

1. Run the script:
   ```
   python BreastCancer_classification.ipynb
   ```

2. The script will:
   - Load the dataset
   - Train an SVM model
   - Display the model's performance metrics
   - Provide an example prediction using mean feature values

3. To predict for a new patient:
   - Uncomment the last four lines of the script
   - Run the script and follow the prompts to input feature values

## Model Details

- **Algorithm**: Support Vector Machine (SVM)
- **Kernel**: RBF (Radial Basis Function)
- **Scaling**: StandardScaler is used to normalize the feature values

## File Descriptions

- `BreastCancer_classification.ipyb`: Main script containing the model and prediction functions
- `README.md`: This file, providing project information and instructions

## Future Improvements

1. Implement cross-validation for more robust model evaluation
2. Experiment with different machine learning algorithms (e.g., Random Forest, Neural Networks)
3. Create a simple web interface for easy predictions
4. Add data visualization to explore feature importance and relationships

Feel free to contribute to this project by submitting pull requests or opening issues for suggestions and bug reports.
