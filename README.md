# Customer Churn Prediction Using Machine Learning

## Overview
Customer churn is a major challenge for subscription-based and service-driven businesses, where retaining existing customers is often more cost-effective than acquiring new ones. This project builds a **machine learning model** to predict customer churn and estimate the likelihood that a customer will leave a service.

The model outputs **probability-based predictions**, enabling data-driven and flexible business decisions rather than rigid binary outcomes.

---

## Objectives
- Predict whether a customer is likely to churn
- Estimate churn risk using probability scores
- Evaluate model performance using industry-standard metrics
- Build a reproducible and interpretable ML workflow

---

## Dataset
The dataset contains anonymized customer-level information, including:
- Customer demographics
- Subscription and account details
- Service usage patterns
- Binary churn indicator (churned / not churned)

### Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Scaled numerical features
- Selected relevant features for modeling

---

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions and churn patterns
   - Examined class imbalance and correlations

2. **Feature Engineering & Cleaning**
   - Converted categorical variables to numerical form
   - Standardized continuous features

3. **Model Development**
   - Implemented a **Logistic Regression** classifier
   - Generated churn probability predictions

4. **Model Evaluation**
   - Evaluated performance using **ROC-AUC**
   - Analyzed prediction quality across classification thresholds

---

## Results
- Achieved an **ROC-AUC score of approximately 0.75**
- Model effectively distinguishes between churned and retained customers
- Probability-based outputs allow prioritization of high-risk customers

---

## Technologies Used
- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## Business Impact
This model can be integrated into a business analytics pipeline to:
- Identify high-risk customers early
- Support targeted retention campaigns
- Reduce revenue loss due to customer churn
- Enable data-driven customer engagement strategies

---

## Future Improvements
- Experiment with advanced models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Address class imbalance using resampling techniques
- Add explainability tools (SHAP, feature importance)
- Deploy the model as an API or interactive dashboard

---

## How to Run
1. Clone the repository
2. Install required dependencies
3. Open `ChurnPrediction.ipynb`
4. Run all cells to reproduce results

---

## Author
Navtesh Nijhawan
