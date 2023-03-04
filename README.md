# Titanic Disaster Classification Using SVM

This repository contains the code for a classification model using Support Vector Machines (SVM) to predict survival rates of passengers on the Titanic disaster. The code is implemented in Python 3 and Jupyter Notebook, and uses the Titanic dataset provided by Kaggle.

##Installation

To run the code in this repository, you need to have the following libraries installed:

    pandas
    numpy
    sklearn
    matplotlib

You can install them using pip by running the following command in your terminal:

    pip install pandas numpy sklearn matplotlib

Alternatively, you can install the libraries individually as well.

## Usage

To use this code, click on the colab link at the begining of the main notebook, or follow these steps:

    Clone this repository to your local machine
    Open the classification-using-svm.ipynb file using Jupyter Notebook
    Run the code cells in order
    The final output will be a CSV file containing the predictions for survival of passengers in the test set

## Dataset

The Titanic dataset contains information about passengers who were aboard the Titanic during its maiden voyage, including whether they survived or not. The dataset is divided into two parts: train and test.

## Model

The SVM model in this repository uses the radial basis function (RBF) kernel to classify the passengers into survived or not survived. The model is trained using the train set, and the hyperparameters of the model are tuned using GridSearchCV. The performance of the model is evaluated using cross-validation.

## Results

The model achieves an accuracy of around 78.22% on the test set.

## License

This repository is licensed under the MIT License. You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software. However, please include a reference to this repository if you use any of the code.
