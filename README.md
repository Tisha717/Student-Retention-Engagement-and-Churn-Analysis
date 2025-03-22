# Project Title: Student Retention, Engagement, and Churn Analysis

## Overview:
This project aims to analyze student engagement data to identify trends in signups and completions, predict drop-offs, and develop strategies to enhance engagement. The project is divided into **3 sections**, with each section focusing on a specific stage of the data analysis process.

---

## Folder Structure:
├── data/                   
│   ├── SLU_Opportunity_Wise_Dataset.csv         # Raw dataset  
│   ├── Cleaned_Preprocessed_Dataset.xlsx         # Cleaned and preprocessed data  

├── Notebooks/               
│   ├── Data_Cleaning_and_Preprocessing.ipynb     # Data cleaning and feature engineering  
│   ├── Bivariate_Analysis_1.ipynb                 # Bivariate analysis (part 1)  
│   ├── Bivariate_Analysis_2.ipynb                 # Bivariate analysis (part 2)  
│   ├── EDA_and_Data_Visualization.ipynb           # Exploratory Data Analysis and visualizations  
│   ├── Relationships_Between_Variables.ipynb      # Analyzing relationships between variables  
│   ├── Final_Model_File.ipynb                     # Final churn prediction model  
│   ├── Consolidated_Predictive_Models.ipynb        # Consolidated model comparisons  
│   ├── Student_Drop_off_Analysis.ipynb             # Drop-off rate and analysis  

├── Reports/               
│   ├── Data_Cleaning_Report.pdf                   # Report on data cleaning and preprocessing  
│   ├── Exploratory Data Analysis (EDA) Report.docx # Detailed EDA report  
│   ├── Univariate_Analysis_Insights.docx           # Insights from univariate analysis  
│   ├── Churn_Analysis_Report_Week3.docx            # Churn analysis and findings  
│   ├── Dropoff_Analysis_Report.docx                # Drop-off analysis and insights  

├── Presentation/               
│   ├── Student_Retention_Engagement_Churn_Analysis.pptx   # Project presentation  

├── README.md                                      # Project documentation  

---

## ✨ Data Cleaning and Preprocessing:
- Cleaned raw data to ensure consistency and accuracy.
- Handled missing values and standardized categorical data.
- Performed data type corrections and normalization.
- Created new features like **age**, **opportunity_duration**, and **engagement_time**.
- Applied outlier detection and treatment using **IQR** and **boxplots**.
- Validated data for consistency and removed duplicates.

### 💻 Technologies Used:
- Python, Pandas, NumPy
- Jupyter Notebook
- Data Cleaning and Preprocessing Techniques
- Data Validation and Outlier Detection

---

## 📊 Exploratory Data Analysis (EDA) and Visualization:
- Conducted comprehensive **EDA** to identify trends and correlations.
- Performed **univariate and bivariate analyses** to understand variable distributions and pairwise relationships.
- Examined factors influencing **engagement, completion rates, and drop-offs**.
- Created visualizations like **histograms, box plots, scatter plots, and correlation heatmaps** to reveal patterns.
- Analyzed demographic trends (age, gender, country, institution) to understand engagement variations.
- Generated insights from **relationship analysis** between variables.

### 💡 Key Insights:
- **Internships** are the most popular opportunity type but have the highest drop-off rate (~67%).
- **Short-term opportunities** (e.g., competitions) have higher completion rates compared to long-term programs.
- Significant drop-offs were observed around **60-100 days**, indicating a critical engagement period.
- Higher **engagement scores** correlate with better completion rates, emphasizing the need for interactive learning.
- **Gender disparities** exist, with **male learners** having higher drop-off rates than females.

---

## 🔍 Churn and Drop-off Analysis:
- Performed **churn analysis** to identify factors contributing to student disengagement.
- Analyzed student **drop-off rates** across opportunity categories and demographic groups.
- Developed and evaluated multiple predictive models (**Random Forest, SVM, Decision Tree, Logistic Regression**) to forecast churn.
- Selected the **best-performing model (Random Forest)** based on accuracy and interpretability.
- Conducted **feature importance analysis** to identify critical factors influencing churn.

### 💡 Key Insights:
- **Random Forest** emerged as the most accurate model with an accuracy of **99.77%**.
- High drop-off rates were observed in **Internships and Courses** due to long durations and workload mismatches.
- **Teenagers and mid-20s age groups** had the highest drop-off rates, while older participants (30+) showed better retention.
- **Males had higher drop-offs** compared to females, especially in **career-oriented programs**.
- **Health Care Management and Career Essentials** had notable drop-offs, indicating potential course design or engagement issues.
- **High Engagement Scores and Longer Opportunity Durations** correlated with better retention.

---

## 📑 Presentations:
- The complete analysis and findings are summarized in the presentation:
  - **Student Retention, Engagement, and Churn Analysis Presentation** - [View Presentation](Presentation/Student_Retention_Engagement_Churn_Analysis.pptx)
