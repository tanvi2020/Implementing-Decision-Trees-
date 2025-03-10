# Implementing-Decision-Trees-
This project demonstrates the implementation of a Decision Tree from scratch using Python.

## What is a Decision Tree? 
A Decision Tree is a supervised learning algorithm used for classification and regression tasks. It works by recursively splitting the dataset based on the feature that results in the best separation of     classes. The process continues until a stopping criterion is met.

## Steps Implemented:
1. Generating a Synthetic Dataset: A toy dataset with two numerical features (X1, X2) and a binary target variable (0 or 1) is created.

2. Visualizing the Dataset: The data points are plotted to show how they can be classified into two distinct classes.

3. Building the Decision Tree:
    - Selecting the best feature for splitting.
    - Recursively dividing the dataset into smaller subsets.
    - Stopping when the subsets are pure (all instances belong to a single class).

4. Training the Model: The decision tree is trained on the generated dataset.

5. Evaluating the Model: The accuracy of the model is assessed on a test dataset.

6. Visualizing the Decision Boundaries: The decision tree’s classification regions are plotted for better understanding.

## Installation & Requirements
To run this project, you need the following dependencies:
```bash
pip insatll numpy matplotlib
```

## Usage
1. Clone this repository:
```bash
git clone https://github.com/tanvi2020/Implementing-Decision-Trees-.git
cd Implementing-Decision-Trees-
```

2. Open and run the Jupyter Notebook:
```bash
jupyter notebook "Implementing Decision Trees.ipynb"
```

3. Follow the steps inside the notebook to understand how the decision tree is built and evaluated.

## Results
The synthetic dataset is classified into two groups.
The decision tree is trained on this dataset and correctly identifies patterns.
Decision boundaries are visualized to show how the model classifies new points.

## Conclusion
This project provides an intuitive understanding of decision trees and how they classify data. It also demonstrates how simple decision rules can be used to separate different classes effectively.


