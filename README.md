# Project README

## Description

This folder contains a Jupyter Notebook file **A4.ipynb**.\
The notebook is designed to work on image classification tasks,
specifically focused on `Fashion-MNIST` dataset. It includes data preprocessing, model
training, hyperparameter optimization, and evaluation steps.

## Setup Instructions

### Prerequisites

-   Python 3.8 or higher
-   Jupyter Notebook or Jupyter Lab
-   Recommended: Create a virtual environment to manage dependencies.

### Required Python Libraries

Install the following dependencies before running the notebook:

``` bash
pip install numpy pandas scikit-learn torch matplotlib torchvision
```

### Running the Notebook

1.  download the notebook file (`A4.ipynb`).
2.  Open a terminal and activate your Python environment.
3.  Launch Jupyter Notebook or Jupyter Lab:

``` bash
jupyter notebook
```

or

``` bash
jupyter lab
```

4.  Navigate to and open `A4.ipynb`.
5.  Execute the cells step by step to reproduce the workflow.

## Contents of the Notebook

-   **Data Loading**: Loads the dataset.
-   **Preprocessing**: Normalization and data splits.
-   **Building and training a Baseline model**: defines and trains baseline model.
-   **Hyperparameter Optimization** Optimizises the hyperparameters of the model.
-   **Evaluation**: Assesses model performance with accuracy and
    visualization metrics.

## Notes

-   Ensure the dataset is correctly placed in the `kaggle/`
    directory (with files for each training and test set: `fashion-mnist_test`, `fashion-mnist_train`, etc.).
-   Training times may vary depending on hardware performance.
