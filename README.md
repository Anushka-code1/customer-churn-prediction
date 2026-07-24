# customer-churn-prediction
Customer Churn Prediction

#Overview

This project predicts customer churn using machine learning techniques. Customer churn refers to customers who stop using a company's service. By identifying customers likely to churn, businesses can take proactive measures to improve retention and reduce revenue loss.

#Features

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Scaling using StandardScaler
- Multiple Machine Learning Models:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - XGBoost Classifier
- Model Comparison and Evaluation
- Confusion Matrix Visualization
- ROC-AUC Curve Analysis
- Feature Importance Analysis
- Customer Churn Prediction

#Dataset

The dataset contains customer-related information such as:

- Customer ID
- Age
- Gender
- Monthly Spending
- Subscription Length
- Support Interactions
- Churn Status (Target Variable)

#Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost

#Project Workflow

1. Data Loading

- Import dataset
- Check dataset dimensions
- Analyze data types and missing values

2. Exploratory Data Analysis

- Feature distribution analysis
- Churn rate calculation
- Gender-wise churn analysis
- Subscription length analysis
- Correlation heatmap visualization

3. Data Preprocessing

- Remove unnecessary columns
- Split features and target variable
- Train-test split
- Feature scaling

4. Model Training

The following models are trained and compared:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost

5. Model Evaluation

Performance metrics used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

6. Visualization

- Confusion Matrix
- ROC Curves
- Feature Importance Charts
- Distribution Plots

#Results

The project compares multiple machine learning algorithms and selects the best-performing model based on evaluation metrics such as F1 Score and ROC-AUC.

#Installation

git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

Install required packages:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost plotly

Run the Project

jupyter notebook CUSTOMER_CHURN_PREDICTION.ipynb

#Future Improvements

- Hyperparameter tuning
- Deployment using Flask or Streamlit
- Real-time prediction dashboard
- Handling class imbalance techniques
- Advanced feature engineering

#Author

**Name:** Anushka Gupta
**GITHUB:** [Anushka-code1](https://github.com/Anushka-code1)

