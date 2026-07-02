# 💰 Income / Census EDA | Data Cleaning, Feature Engineering & Salary Insights

# 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the **UCI Adult (Census Income) Dataset**. The objective is to analyze demographic and employment-related features that influence whether an individual earns **more than $50K** or **less than or equal to $50K** annually.

The project demonstrates complete data preprocessing, feature engineering, memory optimization, and statistical analysis using Python and its data science ecosystem.

---

# 🎯 Objectives

- Understand the structure of the Adult Census dataset
- Perform data cleaning and preprocessing
- Handle missing values and duplicate records
- Apply feature engineering techniques
- Analyze income distribution across different demographics
- Identify factors influencing salary levels
- Demonstrate efficient Pandas operations and memory optimization

---

# 📊 Dataset Information

| Feature | Details |
|----------|----------|
| Dataset | UCI Adult (Census Income) |
| Source | Kaggle / UCI Machine Learning Repository |
| Rows (Raw) | 48,842 |
| Rows (Cleaned) | 45,175 |
| Columns (Raw) | 15 |
| Columns (Cleaned) | 12 |
| Target Variable | Income (<=50K, >50K) |
| Missing Values | '?' in Workclass, Occupation, Native Country |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Project Structure

```
Income-Census-EDA/
│
├── adult.csv
├── income_census_eda.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── age_distribution.png
│   ├── income_distribution.png
│   ├── workclass_distribution.png
│   ├── gender_income.png
│   ├── age_income_boxplot.png
│   ├── missing_values_heatmap.png
│   └── workclass_salary.png
```

---

# 📈 Exploratory Data Analysis

The project includes the following analyses:

### 🔹 Data Inspection

- Dataset shape
- Top & bottom records
- Data types
- Memory usage
- Statistical summary

### 🔹 Data Cleaning

- Replace '?' with NaN
- Handle missing values
- Remove duplicate records
- Drop unnecessary columns
- Memory optimization using category datatype

### 🔹 Feature Engineering

- Label Encoding of target variable
- Remove redundant columns
- Convert categorical columns to efficient data types

### 🔹 Univariate Analysis

- Age Distribution
- Income Distribution
- Workclass Distribution
- Education Distribution

### 🔹 Bivariate Analysis

- Age vs Income
- Gender vs Income
- Workclass vs Salary
- Education vs Income

### 🔹 Aggregation Analysis

- Highest earning workclass
- Gender salary comparison
- Income distribution by education

---

# 📊 Key Visualizations

- 📈 Age Distribution Histogram
- 📊 Income Distribution
- 📦 Workclass Distribution
- 👨‍💼 Gender Salary Comparison
- 📉 Age vs Income Boxplot
- 🔥 Missing Value Heatmap
- 💰 Workclass Salary Ranking

---

# 🔍 Key Insights

- 📌 76.1% of individuals earn **≤ $50K**, while 23.9% earn **> $50K**.
- 📌 Self-employed incorporated professionals have the highest percentage of high-income earners.
- 📌 Age is positively associated with higher income.
- 📌 Male individuals have a higher proportion of income above $50K than females.
- 📌 HS-grad is the most common education level.
- 📌 Bachelors and Masters degree holders represent a significant high-income segment.
- 📌 Data cleaning removed 3,620 missing-value rows and 47 duplicate records.
- 📌 Memory optimization reduced storage usage by converting categorical variables.

---

# 🧹 Data Cleaning Steps

- Checked missing values
- Replaced '?' with NaN
- Removed missing records
- Removed duplicate rows
- Dropped:
  - educational-num
  - capital-gain
  - capital-loss
- Encoded target variable
- Optimized categorical data types

---

# 💡 Business Questions Answered

- Which age group earns the highest income?
- What percentage of people earn above $50K?
- Which workclass has the highest salary?
- Does gender influence salary?
- How many people hold Bachelors or Masters degrees?
- What is the age distribution of the workforce?
- Which columns contain missing values?
- How can memory usage be optimized?

---

# 📚 Python Concepts Used

- Pandas Data Analysis
- NumPy
- Missing Value Handling
- Feature Engineering
- Label Encoding
- GroupBy Aggregation
- Value Counts
- Data Filtering
- Boolean Indexing
- Histograms
- Boxplots
- Heatmaps
- Memory Optimization
- Data Cleaning Pipeline

---

# 🚀 Future Improvements

- 🤖 Income Prediction using Machine Learning
- 📊 Interactive Streamlit Dashboard
- 🌲 Random Forest Classifier
- 🚀 XGBoost Classifier
- 📉 Feature Importance Analysis
- ⚖️ Class Imbalance Handling using SMOTE
- 📈 SHAP Explainability
- 🔍 Fairness and Bias Analysis

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/income-census-eda.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install manually

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

# 📸 Sample Output

Create an **images** folder and add screenshots from your notebook.

```
images/
├── age_distribution.png
├── income_distribution.png
├── workclass_distribution.png
├── gender_income.png
├── age_income_boxplot.png
├── missing_values_heatmap.png
└── workclass_salary.png
```

---

# 👨‍💻 Author

**Prince Maheta**

📊 Aspiring Data Scientist | Data Analyst

🔗 **GitHub:** https://github.com/princemaheta2627-glitch

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is created for educational and portfolio purposes.
