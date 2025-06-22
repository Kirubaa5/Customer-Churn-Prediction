
#  Customer Churn Prediction – Data Analytics Project

##  Objective

To analyze customer churn behavior using telco customer data, gain business insights, and use predictive modeling to identify customers who are likely to churn. This project is a **Data Analytics Project** that focuses on **EDA, visualization, insights**, and basic machine learning for churn prediction.

---

##  Dataset Overview

- **Source**: Telco Customer Churn dataset
- **Records**: 7,000+ customer entries
- **Features**: Demographic details, service usage, account info, and churn status
- **Target Variable**: `Churn` (Yes/No)

---

##  Step 1: Data Cleaning and Preprocessing

- Removed duplicates and null values
- Converted `TotalCharges` column to numeric
- Dropped the `customerID` column
- Applied One-Hot Encoding to categorical features
- Standardized column types and fixed inconsistent labels

---

##  Step 2: Exploratory Data Analysis (EDA)

- Visualized churn distribution using pie and bar plots
- Explored relationships between churn and:
  - Monthly Charges
  - Tenure
  - Contract Type
- Used **Seaborn heatmap** to show feature correlations
- Found patterns:
  - Customers with month-to-month contracts churn more
  - Higher monthly charges = higher churn risk
  - Longer tenure = lower churn

---

##  Key EDA Insights

- **Tenure**: Customers who stay longer are less likely to churn
- **Contract Type**: Month-to-month contracts are riskier
- **Internet Service**: Fiber optic users churn more than DSL users
- **Senior Citizens**: Slightly higher churn among older customers

---

##  Step 3: Predictive Modeling

We used 3 basic machine learning models to predict churn:

| Model                 | Accuracy | Use Case |
|----------------------|----------|----------|
| Logistic Regression  | 78.7%    | Simple, fast baseline |
| Decision Tree        | 82–84%   | Rule-based explanation |
| Random Forest        | ~85%     | Best performing model |

###  Evaluation Metrics:
- **Accuracy Score**
- **Confusion Matrix**
- **Precision, Recall, F1-Score**
- Final model:  **Random Forest**

---

##  Visualizations

- Count plots and bar charts for churn trends
- Correlation Heatmap for feature relationships
- Confusion Matrix to visualize model prediction accuracy

---

##  Business Use

This analytics can help:
- Identify customers who are about to leave
- Trigger offers or loyalty programs for high-risk segments
- Guide the marketing team to focus on at-risk profiles

---

##  Conclusion

This project showed how **data analytics** combined with **basic ML** can help businesses:
- Understand customer behavior
- Predict churn
- Reduce loss and increase customer retention

---

## 🛠 Tools & Technologies

- **Language**: Python
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: Scikit-learn
- **Platform**: Jupyter Notebook

Updated README with Data Analytics details






