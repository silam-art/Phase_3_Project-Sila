# 🩺 Flu Shot Prediction Project

## 📌 Overview

This project explores the use of predictive modeling to understand and improve flu vaccine uptake. Vaccines are a cornerstone of public health, yet their adoption is often inconsistent due to a complex mix of personal beliefs, misinformation, and systemic barriers. The COVID-19 pandemic underscored the urgency of addressing these challenges, making it clear that understanding vaccine hesitancy is not just important—it can be life-saving.

Using historical data on flu vaccination behavior, this project aims to identify the key factors influencing vaccine uptake and develop a model that can predict who is likely to get vaccinated. These insights can then inform targeted outreach strategies, especially in low-resource settings where efficient allocation of healthcare resources is critical.

## 🎯 Business Objectives

The project is driven by the following key questions:

1. Who is likely to get vaccinated and why?
2. What behaviors are associated with poor vaccine uptake?
3. What strategies can be recommended to overcome these barriers, especially during the rollout of new vaccines?

By answering these questions, the project supports the design of proactive, data-driven public health interventions.

## 📊 Data Understanding

- **Source**: The dataset was obtained from Kaggle.
- **Size**: 26,707 rows × 38 columns.
- **Data Types**:
  - 23 float columns
  - 3 integer columns
  - 12 object (categorical) columns
- **Preprocessing**:
  - Dropped irrelevant or low-quality columns
  - Handled missing values
  - Converted categorical variables into numerical format for modeling

## 🔍 Data Analysis Highlights

- **Vaccine Uptake Distribution**: Fairly balanced between vaccinated and unvaccinated individuals.
- **Age Factor**: Uptake increases with age, suggesting older individuals are more likely to get vaccinated.
- **Correlation Analysis**: A heatmap revealed strong correlations among several features, indicating potential predictors worth exploring in the model.

## 🤖 Modeling Approach

- **Model Used**: Random Forest and Lasso Regression
- **Feature Importance**:
  - Features with positive coefficients increase the likelihood of vaccination.
  - Features with negative coefficients decrease it.
  - Top features were identified to guide targeted interventions.
- **Model Evaluation**:
  - Random Forest outperformed Lasso Regression across all metrics, particularly in recall and F1 score.
  - ROC curves confirmed Random Forest’s superior balance between sensitivity and specificity.

## ✅ Recommendations

1. **Leverage Healthcare Providers for Advocacy**  
   Doctors’ recommendations are among the strongest predictors of vaccine uptake. Equip healthcare workers with tools and training to advocate effectively.

2. **Address Misconceptions About Vaccine Safety and Effectiveness**  
   Public health messaging should directly counter misinformation, especially fears about vaccine side effects and doubts about efficacy.

3. **Target Low-Uptake Regions and Occupations**  
   Geographic and occupational factors significantly influence vaccine behavior. Tailored outreach and workplace vaccination programs can help bridge these gaps.

## 🚀 Next Steps

- Deploy the Random Forest model for real-world use.
- Continuously refine the model as new data becomes available.
- Conduct further analysis on communication strategies to determine the most effective outreach methods.
- Collaborate with public health agencies to implement data-driven interventions.

## 📫 Contact

- **Author**: Sila Joy Monthe  
- **Email**: sila.j.monthe@gmail.com  
- **GitHub**: [github.com/silam-art](https://github.com/silam-art)# Phase_3_Project-Sila
Phase 3 Project
