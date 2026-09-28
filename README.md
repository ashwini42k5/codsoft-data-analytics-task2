# CodSoft Data Analytics Internship: Task 2, Exploratory Data Analysis (EDA)

## 📌 Overview
This project is part of the **CodSoft Data Analytics Internship**.
The goal of Task 2 was to explore a dataset using descriptive statistics and visualizations, identify trends, distributions and relationships, detect outliers, and answer key business questions.

## 📂 Dataset
**IBM HR Analytics Employee Attrition Dataset** (from Kaggle), cleaned in Task 1.
- 1,470 employee records
- 32 columns after cleaning, covering demographics, job role, satisfaction, income and attrition status

## 🛠️ Tools & Libraries
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab

## 🔍 Analysis Performed
1. **Descriptive statistics:** used `.shape`, `.describe()` and `.describe(include='object')` to summarize numeric and categorical columns.
2. **Distributions:** histograms for Age and MonthlyIncome, and a count plot of Attrition.
3. **Relationships:** correlation heatmap of numeric columns, plus attrition compared across OverTime and Department.
4. **Outlier detection:** boxplots and the IQR method on MonthlyIncome, TotalWorkingYears, YearsAtCompany and YearsSinceLastPromotion.
5. **Business questions:** answered using group-wise summary statistics (attrition by job role, income, job level, job satisfaction and promotion).

## 📊 Key Findings
- **Overall attrition** was 16.1%.
- **Overtime** employees had 30.5% attrition, compared with 10.4% for those who did not work overtime.
- **Sales Representatives** had the highest attrition (39.8%), while **Research Directors** had the lowest (2.5%).
- Employees who left earned less on average (4,787 vs 6,833 per month).
- Income rises steadily with job level, from 2,787 at level 1 to 19,192 at level 5.
- Attrition falls as job satisfaction rises, from 22.8% to 11.3%.
- MonthlyIncome had 114 outliers, mostly senior-level employees, so they were kept as valid data.
- MonthlyIncome and JobLevel were very highly correlated (about 0.95).

## ✅ Outcome
The analysis shows that overtime, job role, income and job satisfaction are closely linked to employee attrition. These insights can guide retention efforts, such as reviewing overtime workload and pay for high-attrition roles.

## 📁 Files in this Repository
- `CodSoft_Task2_EDA.ipynb`: full notebook with code, charts and the findings report
- `cleaned_HR_Employee_Attrition.csv`: cleaned dataset used for the analysis

---
**#CodSoft #DataAnalytics #Python #EDA #Pandas #Internship**
