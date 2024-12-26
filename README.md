---
title: "Customer Churn Prediction"
output: github_document
---

# Customer Churn Prediction

## Project Overview
- This project predicts customer churn in the telecommunications industry using machine learning models.
- Focuses on identifying churn drivers and providing actionable insights for customer retention.

## Key Features
- **Data Analysis**: Understanding customer behavior using demographic, billing, and service-related data.
- **Model Implementation**: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting classifiers.
- **Model Evaluation**: Metrics such as Accuracy, Precision, Recall, F1-Score, and AUC-ROC.
- **Visualizations**: Graphs to interpret feature importance and trends.
- **Recommendations**: Suggestions to reduce churn and improve retention.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: `pandas`, `NumPy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Tools**: Jupyter Notebook, Anaconda

## Dataset
- **Source**: Telco Customer Churn dataset.
- **Details**:
  - 7,043 customer records with 21 features.
  - Includes demographic, account, service, and churn target variable.

## Project Workflow

### 1. Data Preprocessing
- Cleaned data by handling missing values.
- Encoded categorical variables.
- Scaled numerical features for consistency.

### 2. Exploratory Data Analysis (EDA)
- Visualized trends for key features like tenure, charges, and contract type.
- Used correlation heatmaps to identify relationships between features.

### 3. Feature Engineering
- Created tenure groups and high-spending indicators.
- Enhanced feature importance for better model performance.

### 4. Model Development
- Implemented the following models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- Applied hyperparameter tuning for optimal performance.

### 5. Model Evaluation
- Compared models using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - AUC-ROC

### 6. Insights and Recommendations
- Identified key churn factors: month-to-month contracts, high monthly charges, short tenure.
- Suggested retention strategies like loyalty rewards and pricing adjustments.

## Results
- **Best Model**: Random Forest with 73% accuracy and 0.83 AUC.
- **Key Insight**: Customers with short tenure and high charges are more likely to churn.

## How to Run the Project

### Clone the repository
```bash
git clone https://github.com/rohan58421/customer-churn-prediction.git
cd customer-churn-prediction
**

# Project Structure
notebooks/: Contains Jupyter notebooks for data preprocessing, EDA, and modeling.
data/: Includes the dataset used for the project.
results/: Contains model evaluation metrics and visualizations.
README.md: Project documentation.

#Contributing
Contributions are welcome! Fork the repository, create a branch, and submit a pull request.
