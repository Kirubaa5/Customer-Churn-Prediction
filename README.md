
Customer Churn Prediction – Data Analytics Project

 Objective
To build a predictive model that identifies customers likely to churn using telco customer data. This helps businesses reduce customer loss and improve retention strategies.

---

## Step 1: Data Preprocessing
- Loaded Telco dataset and cleaned missing values
- Converted categorical variables using **one-hot encoding**
- Removed unnecessary columns (e.g., `customerID`)

---

##  Step 2: Exploratory Data Analysis (EDA)
- Visualized churn distribution, monthly charges, tenure
- Created a **correlation heatmap** to understand relationships
- Found key churn drivers: **tenure, monthly charges, contract type**

---

##  Step 3: Model Building & Evaluation
Built and compared 3 machine learning models:

| Model                | Accuracy | Best For                        |
|----------------------|----------|---------------------------------|
| Logistic Regression  | 78.7%    | Fast, interpretable baseline    |
| Decision Tree        | 80–85%   | Good for rule-based decisions   |
| Random Forest        | ~85%     | Best performance overall        |

Evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Precision, Recall, F1-score**

---

##  Key Insights
- Customers with **shorter tenure** are more likely to churn
- **Month-to-month contracts** lead to higher churn rates
- Higher **monthly charges** also correlate with churn

---

##  Conclusion
The Random Forest model achieved the best performance with ~85% accuracy. It can now be used to:
- Predict churn
- Trigger retention offers or interventions

---

##  Tools Used
- Python (Pandas, NumPy, Scikit-learn)
- Seaborn & Matplotlib for data visualization
- Jupyter Notebook for development
