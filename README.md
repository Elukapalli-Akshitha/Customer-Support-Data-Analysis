# 📊 Customer Satisfaction Analysis & Prediction using Machine Learning

## 📌 Project Overview
This project focuses on analyzing customer service data to understand the key factors affecting customer satisfaction (CSAT) and building machine learning models to predict customer satisfaction levels.

The workflow includes:
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Machine Learning Model Building  
- Model Evaluation & Optimization  

---

## 🎯 Objective
The main objective of this project is to:
- Identify factors impacting customer satisfaction  
- Analyze customer service performance  
- Predict CSAT scores using machine learning models  
- Provide actionable business insights  

---

## 📂 Dataset Description
The dataset contains customer support interaction details such as:
- Channel Name  
- Category & Sub-category  
- Customer Remarks  
- Order Date & Issue Timelines  
- Customer City  
- Product Category  
- Item Price  
- Connected Handling Time  
- Agent Details (Agent, Supervisor, Manager)  
- Tenure Bucket  
- Agent Shift  
- CSAT Score  

---

## 🔧 Tech Stack
- **Python 3.9**
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Machine Learning  

---

## 📊 Exploratory Data Analysis (EDA)
EDA was performed using:
- Univariate Analysis  
- Bivariate Analysis  
- Multivariate Analysis  

### Key Insights:
- Faster response time leads to higher customer satisfaction  
- Higher handling time negatively impacts CSAT  
- Certain product categories have lower satisfaction scores  
- Agent performance plays a crucial role  

---

## ⚙️ Data Preprocessing
- Missing values handled using median (numerical) and mode (categorical)  
- Categorical variables encoded using Label Encoding  
- Feature engineering (response time, order hour, etc.)  
- Data scaling using StandardScaler  
- Train-Test split (80:20)  

---

## 🤖 Machine Learning Models

### 1. Logistic Regression
- Used as baseline model  
- Moderate performance  

### 2. Decision Tree
- Captures non-linear patterns  
- Improved performance but slightly overfitting  

### 3. Random Forest (Best Model)
- Ensemble technique  
- Highest accuracy and stability  
- Handles feature interactions effectively  

---

## 📈 Model Evaluation Metrics
- **Accuracy** – Overall prediction correctness  
- **Precision** – Avoid false positives  
- **Recall** – Identify dissatisfied customers  
- **F1 Score** – Balance between precision & recall  

---

## 🏆 Final Model
**Random Forest Classifier** was selected as the final model due to:
- Best performance across all metrics  
- Robustness and stability  
- Better handling of complex relationships  

---

## 💡 Business Impact
- Helps identify dissatisfied customers early  
- Improves customer service efficiency  
- Reduces response time  
- Enhances customer experience and retention  

---

## 🚀 Future Improvements
- Deploy model using Flask/Streamlit  
- Use real-time prediction system  
- Implement advanced models like XGBoost  
- Improve feature engineering 
