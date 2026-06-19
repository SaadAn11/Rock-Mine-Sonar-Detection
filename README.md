Rock vs Mine Sonar Detection

A machine learning project that classifies underwater objects as rocks or mines using sonar frequency data and Logistic Regression.

About the Dataset

The dataset used is the UCI SONAR Dataset, which contains 208 samples with 60 features each. Each feature represents the energy of a sonar signal at a particular frequency angle. The label is either R (Rock) or M (Mine).

What This Project Does

Loads and explores the SONAR dataset
Performs basic EDA (class distribution, feature means by class)
Splits data into training and test sets
Trains a Logistic Regression model
Evaluates accuracy on both training and test data
Includes a prediction system for new input data


Libraries Used

NumPy
Pandas
scikit-learn


How to Run

Clone this repository
Download the dataset and place it in the same folder as the notebook
Update the file path in the notebook to match your local path
Run all cells in order


Results

Split    ~ Accuracy
Training ~ 83%
Test     ~ 76%
