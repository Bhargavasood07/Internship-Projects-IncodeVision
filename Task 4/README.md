# 📊 Customer Churn Prediction using Machine Learning

## 📖 Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom companies, banks, insurance providers, and SaaS platforms. This project aims to predict whether a customer is likely to leave a service using Machine Learning algorithms.

The project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and customer churn prediction.

---

# 🎯 Project Objectives

* Predict customer churn using supervised machine learning.
* Clean and preprocess customer data.
* Handle missing values and duplicate records.
* Encode categorical features for model training.
* Compare multiple machine learning algorithms.
* Evaluate model performance using standard classification metrics.
* Identify important factors influencing customer churn.
* Predict whether a new customer is likely to churn.

---

# 📂 Dataset

This project uses the **Telco Customer Churn Dataset**.

### Dataset Features

* Customer ID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn (Target Variable)

### Target Variable

* **Churn**

  * Yes = Customer leaves the service
  * No = Customer stays

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost (Optional)
* Jupyter Notebook / Google Colab

---

# 📚 Libraries Used

```python
pandas
numpy
matplotlib
seaborn

sklearn.model_selection
sklearn.preprocessing
sklearn.linear_model
sklearn.ensemble
sklearn.metrics

xgboost
```

---

# 📁 Project Structure

```text
Customer_Churn_Prediction/
│
├── Customer_churn_prediction.ipynb
├── Customer churn dataset.csv
├── README.md
└── output_images/
```

---

# 🔄 Machine Learning Workflow

```text
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Handle Missing Values
      │
      ▼
Remove Duplicates
      │
      ▼
Feature Encoding
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Correlation Analysis
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Customer Prediction
```

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Removed duplicate records
* Handled missing values
* Converted TotalCharges to numeric format
* Label encoded categorical features
* Selected features and target variable
* Split data into training and testing datasets

---

# 📊 Exploratory Data Analysis

Performed:

* Dataset inspection
* Missing value analysis
* Correlation analysis
* Feature importance analysis

---

# 🤖 Machine Learning Models

The following models were implemented:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier (Optional)

---

# 📈 Model Evaluation

Models were evaluated using:

* Accuracy
* Recall
* ROC-AUC Score
* Confusion Matrix
* Classification Report

---

# 📉 Visualizations

The notebook includes:

* Correlation Heatmap
* Confusion Matrix
* Feature Importance Plot

These visualizations help understand customer behavior and the factors contributing to churn.

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Move into the project folder:

```bash
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

---

# ▶️ Usage

Run the notebook:

```bash
jupyter notebook Customer_churn_prediction.ipynb
```

or open it in **Google Colab**.

Execute all notebook cells sequentially.

---

# 📌 Key Features

* Customer Churn Prediction
* Data Cleaning & Preprocessing
* Label Encoding
* Correlation Analysis
* Multiple Machine Learning Models
* Feature Importance Visualization
* Confusion Matrix
* ROC-AUC Evaluation
* Customer Prediction Interface

---

# 🎓 Learning Outcomes

This project demonstrates practical knowledge of:

* Supervised Machine Learning
* Classification Algorithms
* Logistic Regression
* Random Forest
* XGBoost
* Data Cleaning
* Feature Engineering
* Model Evaluation
* Customer Retention Analytics
* Business Intelligence

---

# 🔮 Future Improvements

* Hyperparameter Tuning
* SMOTE for Class Imbalance
* Streamlit Dashboard
* Flask API Deployment
* Real-time Customer Churn Prediction
* SHAP Explainability
* Automated Model Selection

---

# 👨‍💻 Author

**Bhargava Sood**

AI & Data Science Enthusiast
Machine Learning | Data Analytics | Python Developer

---

# 📄 License

This project is developed for educational and academic purposes.
