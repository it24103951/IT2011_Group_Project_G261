# **IT2011 AI/ML Project - Progress Review 1**

This repository contains the work for Progress Review 1 of the IT2011 AI/ML group assignment, focusing on data preprocessing and exploratory data analysis (EDA) for predicting student academic performance based on habits and environmental factors.

**## Project Overview**

Objective: Develop a predictive model for student exam scores using a dataset of 1,001 records and 15+ features (e.g., study hours, attendance, mental health rating).
Dataset: student_habits_performance.csv sourced from Kaggle, cleaned of missing values and duplicates.
Stage: Post-proposal (presented week of August 11, 2025); current focus is preprocessing and EDA for the viva on August 26, 2025.
Tools: Python (Jupyter Notebook), pandas, numpy, matplotlib, seaborn, scikit-learn.

Group Members and Contributions

Gunarathne S.P.T (IT24104287): Handling missing data (imputation with mean/mode) + age distribution histogram.
Mudalige M.M.R.L (IT24102164): Encoding categorical variables (label/one-hot) + exam score by gender boxplot.
Rathnayaka R.M.D.D (IT24103951): Outlier removal (IQR method) + correlation matrix heatmap.
Dissanayake S.D.D.H (IT24104104): Normalization/scaling (StandardScaler) + study hours vs exam score scatter plot.
Siriwardana A.W.T.B (IT24103991): Feature engineering (total screen time) + screen time distribution histogram.
Gamage K.H.N.H (IT24103739): Feature selection (SelectKBest) + pairplot of top features.

How to Run
Ensure the dataset is in data/raw/.
Open the notebook in Jupyter and execute cells sequentially.
Review preprocessing steps, EDA visualizations, and the integrated pipeline at the end.

Instructions to Add

Copy the text above into a new file named README.md in your IT2011_Group_Project_G261/ folder.
Save it.
(Optional) If using Git, commit with:
text

`git add README.md
git commit -m "Added README.md"
git push`