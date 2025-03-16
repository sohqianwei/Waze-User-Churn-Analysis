# Waze User Churn Analysis

*A project from the Google Advanced Data Analytics course.*

## Project Overview
This project analyses **user churn behaviour** for Waze using historical data. The goal is to **predict whether a user will churn** based on behavioural patterns.

### **Key Objectives:** 
- Perform **exploratory data analysis (EDA)** on Waze user behaviour.
- Engineer relevant **features** to improve model performance. 
- Develop **classification models** (Logistic Regression, Random Forest, XGBoost).
- Evaluate models using **precision, recall, and F1-score**.
- Extract **business insights** to reduce churn. 

---

## Dataset
- The dataset consists of **user interaction logs** from Waze.
- Features include **trip frequency session duration, navigation usage**, and **demographic data**.
- Due to data privacy, sample/mock datasets are used for demonstration. 

---

## Tech Stack
- **Python** (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn)
- **Jupyter Notebooks** for data analysis

## Exploratory Data Analysis (EDA)
EDA includes: 
- **Distribution of active vs. churn users**
- **Trip frequency trends & navigation habits**
- **Correlation heatmaps to identify key churn drivers**

## 🚀 How to Reproduce
### **1. Clone the Repository**
```bash
git clone git@github.com:sohqianwei/Waze-User-Churn-Analysis.git
cd Waze-User-Churn-Analysis
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run Jupyter Notebook**
```bash
jupyter notebook
```
- Open `notebooks/waze_churn_analysis.ipynb` and run the cells.

