# customer-churn-prediction



## Project Overview
This project focuses on understanding customer churn and predicting which customers are likely to leave a company’s service. The analysis and model-building process involve data exploration, feature engineering, and the application of machine learning techniques to predict churn. The insights derived from this project can be used to guide strategic decisions aimed at reducing churn rates and improving customer retention.

## Project Objectives
- Identify key factors influencing customer churn.
- Build a predictive model to classify customers as "churn" or "non-churn."
- Provide actionable recommendations based on insights derived from the analysis.

## Data Description
The dataset used for this project contains the following features:
- **CustomerID**: Unique ID for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Tenure**: Number of months the customer has stayed with the company.
- **Balance**: Account balance of the customer.
- **Products**: Number of products held by the customer.
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No).
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No).
- **EstimatedSalary**: Estimated salary of the customer.
- **Exited**: Whether the customer churned (1 = Yes, 0 = No).

## Analysis and Modeling
1. **Exploratory Data Analysis (EDA)**:
   - Visualized customer demographics, account information, and behavioral patterns.
   - Analyzed correlations between features and the target variable (churn).

2. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Performed feature scaling and encoding of categorical variables.

3. **Feature Engineering**:
   - Created new features based on domain knowledge to improve model performance.

4. **Modeling**:
   - Built and evaluated several machine learning models, including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Gradient Boosting
   - Used cross-validation and hyperparameter tuning to optimize model performance.

5. **Evaluation Metrics**:
   - Accuracy, precision, recall, F1-score, and ROC-AUC were used to evaluate model performance.

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

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/churn-analysis.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `churn_analysis.ipynb` to explore the analysis and model-building process.

## Conclusion
This churn analysis project provides valuable insights into customer behavior and presents a predictive model that can be applied in real-world scenarios to reduce churn rates and enhance customer retention strategies.

