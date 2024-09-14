

# Customer Churn Prediction

## Table of Contents

### **Data Collection and Preprocessing**
- Importing Essential Libraries and Modules
- Data Cleaning Process
- Handling Missing Data
- Merging Datasets

### **Exploratory Data Analysis**
- Formulating Hypotheses
- Analysis of Categorical Features
- Examination of Continuous Features
- Conclusions from EDA and Hypothesis Validation

### [**Feature Selection and Outlier Detection**](#feature-selection-and-outlier-detection)
- Engineering New Features
- Identifying and Addressing Outliers

### [**Modeling**](#modeling)
- Splitting Data into Training and Testing Sets
- Implementing a Baseline Model with Decision Tree
- Developing a Random Forest Model
- Optimizing Random Forest Model Parameters
- Assessing Feature Importance in Random Forest

### [**Model Performance and Evaluation**](#model-performance-and-evaluation)
- Visual Representation of Model Performance
- Evaluation Metrics for Classification Models
- Comparative Analysis: Random Forest vs. Baseline Model
- Comparison of Tuned Random Forest with Baseline and Initial Models

### [**Store-specific Sales Predictions**](#store-specific-sales-predictions)
- Detailed Predictions for Individual Stores

### [**Conclusion**](#conclusion)
- Summary of Findings

### [**Recommendations**](#recommendations)
- Insights and Suggestions Based on Analysis

## Introduction

This project focuses on predicting customer churn, which refers to customers who stop using a company's services or products. Accurate churn prediction is crucial for businesses to take proactive measures to retain customers and improve satisfaction. The project uses advanced machine learning techniques to build models that can predict customer churn based on historical data.

## Project Overview

- **Objective**: To develop a machine learning model capable of accurately predicting customer churn.
- **Techniques Used**: Data preprocessing, feature engineering, model training, and evaluation.
- **Models Explored**: Decision Trees, Random Forest, Gradient Boosting, Neural Networks.

## Dataset

The dataset used in this project contains various customer attributes relevant to churn prediction. The columns are:

- **state**: Geographic state of the customer.
- **account_length**: Length of the customer's account in months.
- **area_code**: Area code for the customer’s phone number.
- **international_plan**: Indicates if the customer has an international plan (Yes/No).
- **voice_mail_plan**: Indicates if the customer has a voice mail plan (Yes/No).
- **number_vmail_messages**: Number of voice mail messages.
- **total_day_minutes**: Total minutes of calls during the day.
- **total_day_calls**: Total number of calls made during the day.
- **total_day_charge**: Total charge for day calls.
- **total_eve_minutes**: Total minutes of calls during the evening.
- **total_eve_calls**: Total number of calls made during the evening.
- **total_eve_charge**: Total charge for evening calls.
- **total_night_minutes**: Total minutes of calls during the night.
- **total_night_calls**: Total number of calls made during the night.
- **total_night_charge**: Total charge for night calls.
- **total_intl_minutes**: Total minutes of international calls.
- **total_intl_calls**: Total number of international calls.
- **total_intl_charge**: Total charge for international calls.
- **number_customer_service_calls**: Number of calls to customer service.
- **churn**: Target variable indicating whether the customer has churned (1 for Yes, 0 for No).

## Modeling

The project explores several machine learning models to find the best performer:

1. **Decision Trees**: A tree-based model that splits the data based on feature values.
2. **Random Forest**: An ensemble method combining multiple decision trees for improved accuracy.
3. **Gradient Boosting**: Builds trees sequentially to correct errors from previous models.
4. **Neural Networks**: Captures complex patterns through deep learning approaches.

## Model Performance and Evaluation

For classification models, performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and the ROC-AUC score. These metrics provide a more comprehensive view of the model's ability to correctly classify instances of churn and non-churn.

### **Evaluation Metrics:**

- **Accuracy**: The ratio of correctly predicted instances to the total number of instances. It measures how often the model is correct.

- **Precision**: The ratio of true positive predictions to the sum of true positive and false positive predictions. It indicates the proportion of positive identifications that were actually correct.

- **Recall (Sensitivity)**: The ratio of true positive predictions to the sum of true positive and false negative predictions. It shows how well the model can identify positive instances.

- **F1-Score**: The harmonic mean of precision and recall. It provides a balance between precision and recall, especially useful when the class distribution is imbalanced.

- **ROC-AUC Score**: The area under the Receiver Operating Characteristic curve. It measures the model's ability to distinguish between classes across different threshold values.

### **Model Evaluation Steps:**

1. **Confusion Matrix**: Provides a summary of prediction results, showing the number of true positives, false positives, true negatives, and false negatives.

2. **Classification Report**: Includes precision, recall, and F1-score for each class. It offers a detailed look at the performance across different classes.

3. **ROC Curve**: Plots the true positive rate against the false positive rate at various thresholds. The ROC-AUC score quantifies the overall performance.

### **Results:**

- **Baseline Model**: Evaluate using confusion matrix, accuracy, precision, recall, F1-score, and ROC-AUC.

- **Random Forest Model**: Compare with baseline model metrics to assess improvement.

- **Tuned Random Forest Model**: Measure performance post-tuning to ensure optimized results.



## Results
- The final model achieved an accuracy of **[Insert Accuracy]**, with a precision of **[Insert Precision]** and recall of **[Insert Recall]**.
- Key drivers of churn included **[List the most important features]**.

## Recommendations
Based on the analysis, the following strategies can help reduce customer churn:
- **Targeted Retention Campaigns**: Focus on high-risk segments identified by the model.
- **Customer Engagement Programs**: Increase interaction with customers who are less active.
- **Product Bundling**: Offer tailored product packages to customers with higher churn probabilities.

## Tools and Technologies
- **Python**: Data analysis and modeling.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning algorithms.
- **Jupyter Notebook**: Development environment.



## Contact

For any questions or suggestions, please contact:

- **Name**: Musbau, Kazeem Olaitan
- **Email**: kazeemmusbau@gmail.com
- **GitHub**: [https://github.com/kazeemolaitanmusbau](https://github.com/kazeemolaitanmusbau)

---

