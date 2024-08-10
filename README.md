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
  ![image](https://github.com/user-attachments/assets/3c598c62-2c3a-476f-b104-b70a9e0b8f21)


* **Model Accuracy:**  Achieved 95.56% accuracy on the test set.
* **Confusion Matrix:**

![image](https://github.com/user-attachments/assets/2c94d92c-9334-4675-8cf2-e812f8bfb521)


* **Visualization of Petal Length vs Petal Width with Predicted Classes:**

![image](https://github.com/user-attachments/assets/ee509523-815e-492c-b057-1ea805771cc6)


