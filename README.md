# Wine-Quality-Prediction-CodeClause

This GitHub repository contains a Python script for predicting wine quality based on a dataset. The code includes data preprocessing, feature engineering, model building, hyperparameter tuning, evaluation, and visualization.

**Prerequisites**

Before running the code, make sure you have the following libraries installed:

pandas
numpy
matplotlib
seaborn
scikit-learn
You can install them using pip:

pip install pandas numpy matplotlib seaborn scikit-learn

**Dataset**

The code assumes that you have a CSV file named WineQT.csv containing your dataset. Ensure that this file is in the same directory as the script, or provide the correct file path in the code.

**Code Overview**

Here's a brief overview of the code and its functionality:

Data Loading: Load the wine quality dataset from the CSV file.

Data Preprocessing: Split the dataset into features (X) and target (y). Standardize the features using StandardScaler.

Model Selection: Create an ensemble of three models: Random Forest, Gradient Boosting, and Support Vector Machine (SVM). Combine them using a Voting Classifier.

Hyperparameter Tuning: Perform grid search to find the best hyperparameters for the Random Forest model within the ensemble.

Model Evaluation: Evaluate the best model on a test set using accuracy and generate a classification report.

Feature Importance Analysis: Calculate and visualize feature importances using the Random Forest model.

Feature Selection: Select the top k features based on ANOVA F-value.

Visualization: Create various plots, including feature importances, actual vs. predicted quality line chart, residuals plot, histogram of residuals, and probability density plot.

Root Mean Squared Error (RMSE): Calculate and display the RMSE as a performance metric.

**Usage**

Ensure you have the required libraries installed.

Place the WineQT.csv dataset file in the same directory as the script or specify the correct file path in the code.

Run the script, and it will perform data preprocessing, model training, hyperparameter tuning, evaluation, and generate various visualizations.

Review the results and visualizations to analyze the wine quality prediction.

**Customization**

You can customize this code by:

Experimenting with different hyperparameters in the grid search.
Modifying the number of top features selected (variable k).
Adjusting visualization settings to suit your preferences.
Feel free to explore and adapt this code for your own machine learning projects.






