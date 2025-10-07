# Titanic Survival Prediction with Logistic Regression
This project uses the Titanic dataset to explore and predict passenger survival using logistic regression. It focuses on four key features: gender, passenger class, fare paid, and age, to model the probability of survival in a binary classification setup.
## Features

Data exploration and preprocessing (handling missing values, encoding categorical variables like gender).
Visualizations of survival rates by gender and passenger class using bar plots.
Training a logistic regression model with scikit-learn.
Model evaluation using precision, recall, F1-score, and support metrics.
Interpretation of model coefficients to understand feature impacts on survival.

## Requirements

Python 3.x
Libraries:

pandas
numpy
seaborn
matplotlib
scikit-learn

## Results

Model Performance: The logistic regression model achieves approximately 77% accuracy on the test set, with balanced precision and recall for both classes (survived/did not survive).
Key Insights from Coefficients:

Gender (female) strongly increases survival odds.
Higher passenger class reduces survival odds.
Age and fare have minor negative impacts.
