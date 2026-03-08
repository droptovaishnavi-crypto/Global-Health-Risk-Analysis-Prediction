# 🌍 Global Health Risk Analysis & Prediction

A **Data Science & Machine Learning project** that transforms global health data into meaningful insights and predictive models.  
This project analyzes key health indicators and classifies countries into **High, Medium, or Low Health Risk levels** using data preprocessing, exploratory data analysis, machine learning models, and interactive dashboards.

---

## 📌 Project Workflow

### 🔹 Data Collection & Cleaning
- Dataset: **Global Health Statistics (CSV)**
- Removed duplicate records and handled missing values
- Standardized data formats for consistency
- Detected and treated outliers

---

### 🔹 Exploratory Data Analysis (EDA)

Performed statistical and visual analysis to understand patterns in the dataset.

**Analysis performed**
- **Univariate Analysis:** Life Expectancy, Mortality Rate, HIV prevalence, Health Expenditure
- **Bivariate & Multivariate Analysis:** Correlation heatmaps and scatter plots
- **Regional Comparison:** Top 10 countries by Life Expectancy vs Mortality

💡 **Insight:** Countries with higher healthcare spending tend to have higher life expectancy.

---

### 🔹 Feature Engineering & Risk Classification

A new column called **Risk Level** was created to classify countries into:

- High Risk
- Medium Risk
- Low Risk

Risk classification indicators include:

- Life Expectancy
- Maternal and Infant Mortality
- HIV Prevalence
- Tuberculosis Incidence
- Health Expenditure (% of GDP)

A **weighted scoring approach** was used to classify countries into risk levels.

---

### 🔹 Machine Learning Model Development

The following models were implemented and evaluated:

- Logistic Regression
- Random Forest
- XGBoost
- Gradient Boosting
- Decision Tree

**Evaluation Metrics**

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

🎯 **Output:** Prediction of health risk levels for countries based on health indicators.

---

### 🔹 Dashboard & Visualization

An **interactive Power BI dashboard** was created to visualize insights.

**Dashboard features**

- Life Expectancy vs Health Expenditure analysis
- Global disease and mortality mapping
- Regional comparisons
- Top 10 country rankings

**Key Insights**

- Sub-Saharan Africa shows higher disease burden
- Vaccination programs reduce preventable diseases
- Healthcare access gaps exist between rural and urban regions

---

## 🛠️ Tech Stack

**Programming Language**
- Python

**Libraries**
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

**Tools**
- Power BI
- Excel
- CSV datasets

---

## 🚀 Quick Start

Clone the repository

```bash
git clone https://github.com/your-username/global-health-risk-analysis.git
cd global-health-risk-analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the model training script

```bash
python notebooks/model_training.py
```

Open the **Power BI dashboard** file to explore interactive visualizations.

---

## 📊 Key Outcomes

- Cleaned and structured global health dataset
- Comprehensive exploratory data analysis
- Machine learning models for risk prediction
- Interactive Power BI dashboard for visualization

---

## 🌟 Future Improvements

- Deploy the ML model using **Flask / FastAPI**
- Automate dataset updates using **WHO or World Bank APIs**
- Add explainable AI techniques such as **SHAP / LIME**
- Forecast future health risk trends using **time-series models**
