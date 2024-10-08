# Iris Species Classification with Support Vector Machines (SVM)

**Description:**
This R project uses Support Vector Machines (SVM) to classify Iris species. It includes data exploration, model training with hyperparameter tuning, performance evaluation, and visualizations to aid in understanding feature relationships and model accuracy. This serves as a foundational example of how SVM can be applied to various business classification problems.

## Project Overview

This repository contains R code for building and evaluating an SVM model to classify the different species of Iris flowers (setosa, versicolor, and virginica). This project serves as a practical introduction to SVM and its potential applications in a business context.

**Steps:**

1. **Data Exploration:** Analyzing the Iris dataset to understand its features and distributions. We'll use summary statistics and visualizations to gain insights into the data.
2. **Data Preprocessing:** Preparing the data for model training, including handling missing values and potentially scaling features.
3. **Data Splitting:** Dividing the data into training and testing sets to evaluate the model's generalization ability.
4. **Model Training:** Building an SVM model using the training data. We'll experiment with different kernel functions (e.g., linear, polynomial, radial basis function) to find the best fit for the data.
5. **Hyperparameter Tuning:** Optimizing the model parameters using techniques like cross-validation to achieve the best performance.
6. **Model Evaluation:** Assessing the model's accuracy on the testing data using metrics like accuracy, precision, recall, and F1-score.
7. **Visualization:** Creating plots to illustrate feature relationships, decision boundaries, and model predictions.

##  How SVM Can Help Businesses :bulb:

SVM is a powerful machine learning algorithm with various applications in business, including:

* **Customer Churn Prediction:** Identify customers who are likely to churn, allowing businesses to take proactive measures to retain them.
* **Fraud Detection:** Detect fraudulent transactions and activities based on patterns and anomalies in data.
* **Image Classification:** Categorize images for tasks like product recognition or content moderation.
* **Risk Assessment:** Assess the risk associated with loan applications, insurance claims, or other financial decisions.
* **Market Segmentation:** Group customers into segments based on their characteristics and behaviors for targeted marketing campaigns.

This project provides a foundational understanding of SVM, which can be extended to address these and other business challenges.

## Key Features :key:

* **SVM Implementation:** Utilizes the `e1071` package for SVM model training.
* **Hyperparameter Tuning:** Employs the `caret` package for cross-validation and parameter optimization.
* **Visualization:** Includes custom functions for creating insightful plots.
* **Clear Code and Comments:** Provides well-structured and documented code for easy understanding.

## Results :chart_with_upwards_trend:

* **Hyperparameter Tuning Results:**
 ![image](https://github.com/user-attachments/assets/58d8cde3-cd99-4070-958e-ba104426533e)



* **Model Accuracy:**  Achieved 95.56% accuracy on the test set.
* **Confusion Matrix:**
![image](https://github.com/user-attachments/assets/70760604-8bf6-4504-acf5-d97937ec1905)

![image](https://github.com/user-attachments/assets/00964f34-e8a4-46fb-a81c-7992fc1b36f2)




* **Visualization of Petal Length vs Petal Width with Predicted Classes:**

![image](https://github.com/user-attachments/assets/6b0810c8-3940-4d6a-a156-5ed88e75331e)



