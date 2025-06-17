# DATA-SET-SOLVED-QUESTIONS
SOLVED QUESTIONS PYTHON
Project Summary
This repository contains exploratory data analysis (EDA) and statistical analysis of three different datasets:

Clinical Trial Data

Cereal Nutritional Dataset

Insurance Dataset

Each notebook includes data cleaning, visualization, and basic insights aimed at understanding patterns and drawing conclusions.

🔍 1. Clinical Trial Dataset Analysis (clinictrial assignment.ipynb)
✅ Objective:
To compare the effectiveness of a drug (Drug A) versus a placebo in reducing blood pressure.

📊 Steps Performed:
Data Loading:

Loaded a clinical trial dataset using pandas.

Initial Inspection:

Displayed basic info: .head(), .info(), .describe() to understand structure and data types.

Data Cleaning:

Checked for missing values.

Replaced categorical values (e.g., converting “Drug” and “Placebo” groups).

Data Grouping:

Grouped data by group and calculated mean of bp_before and bp_after.

Statistical Testing:

Used independent sample t-test to compare:

Blood pressure before and after within groups.

Compared Drug vs Placebo on effect size.

Insights:

Drug group showed significant improvement in blood pressure reduction compared to the placebo.

🥣 2. Cereal Nutrition Analysis (cereals assignment.ipynb)
✅ Objective:
To analyze and compare nutritional values (like calories, fat, sugar, etc.) in various breakfast cereals.

📊 Steps Performed:
Data Loading:

Loaded CSV data on cereals.

Initial Analysis:

Displayed basic structure and summary stats using .describe() and .info().

Data Cleaning:

Removed missing values and verified data types.

Checked for duplicates.

EDA and Visualization:

Created visualizations using seaborn and matplotlib:

Bar plots for calories and sugar.

Distribution plots (histograms).

Correlation heatmap for nutrient relationships.

Nutritional Ranking:

Ranked cereals based on health metrics such as low sugar and fat.

Highlighted healthier vs less healthy cereals.

Insights:

Certain brands contain higher sugar levels.

Positive correlation between calories and sugar.

🧾 3. Insurance Dataset Analysis (insurance assignment.ipynb)
✅ Objective:
To understand the factors influencing insurance charges (cost), such as age, BMI, smoking status, etc.

📊 Steps Performed:
Data Loading:

Read dataset using pandas.

Initial Analysis:

Used .info() and .describe() to understand column types and summary statistics.

Data Preprocessing:

Converted categorical columns (e.g., sex, smoker, region) into numerical using LabelEncoder.

Exploratory Data Analysis (EDA):

Created visualizations:

Count plots by region, gender.

Distribution plots of age, BMI, charges.

Boxplots comparing charges by smoker status and region.

Regression plots between charges and numerical features.

Correlation Analysis:

Used heatmaps to identify relationships.

Strongest correlation found between charges and smoking status.

Insights:

Smokers pay significantly higher premiums.

BMI and age also play a role in determining insurance charges.

📁 Folder Structure Example
bash
Copy
Edit
.
├── clinictrial assignment.ipynb
├── cereals assignment.ipynb
├── insurance assignment.ipynb
├── README.md
└── datasets/
    ├── clinical_trial.csv
    ├── cereals.csv
    └── insurance.csv
✍️ Suggested README Intro
markdown
Copy
Edit
# Data Analysis Projects 🧠📊

This repository includes exploratory and statistical analysis of three datasets:
1. Clinical trial results evaluating drug efficacy.
2. Breakfast cereal nutritional comparison.
3. Insurance premium factors analysis.

Each notebook demonstrates a typical data science workflow including:
- Data cleaning
- Visualization
- Statistical testing
- Insights generation

Tools used: Python, Pandas, Matplotlib, Seaborn, Scipy

## 🔗 Notebooks
- [Clinical Trial Analysis](clinictrial assignment.ipynb)
- [Cereal Nutrition Analysis](cereals assignment.ipynb)
- [Insurance Charges Analysis](insurance assignment.ipynb)
