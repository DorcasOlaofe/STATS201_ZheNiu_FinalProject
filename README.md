# Predicting Obesity Risk Using Machine Learning

# Project Information

**Author:** Zhe Niu, Data Science, 2024, Duke Kunshan University  
**Instructor:** Prof. Luyao Zhang, Duke Kunshan University  
**Disclaimer:** This project is a submission for the Final Project in STATS201 Introduction to Machine Learning for Social Science, 2023 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.  
**Acknowledgments:** I would like to express my deepest gratitude to Prof. Luyao Zhang for her invaluable guidance and insights throughout this project. Additionally, I am grateful to my peers, particularly [Name of Peers], for their support and constructive feedback during the project development phase. Special thanks to the Duke Kunshan University's Data Science staff, including [Staff Names], for providing the necessary resources and tools for completing this project.

## Project Summary

### Background/Motivation
The global increase in obesity rates poses significant public health challenges, linked to chronic diseases such as diabetes, cardiovascular diseases, and various forms of cancer. This project aims to leverage machine learning techniques to predict obesity risk levels effectively and identify key factors contributing to obesity.

### Research Questions
1. How can machine learning models be effectively utilized to predict obesity risk levels based on a comprehensive set of features?
2. What are the most influential features in determining obesity risk levels?

### Application Scenario (Data Source)
The dataset for this project was sourced from the "Multi-Class Prediction of Obesity Risk" competition on Kaggle. It encompasses a wide array of features, including demographics, dietary habits, physical activity, and genetic factors, making it an ideal dataset for exploring obesity risk predictions.

### Methodology
Our methodology extends beyond current literature and ChatGPT's capabilities by implementing an innovative approach that combines ensemble machine learning techniques (Random Forest, LightGBM, XGBoost) with advanced feature importance evaluation methods (SHAP values). We conducted rigorous data preprocessing, hyperparameter tuning using the Optuna framework, and employed cross-validation to enhance model robustness.

### Results
The XGBoost model emerged as the top performer, achieving an accuracy and F1-score of 0.905 and 0.894, respectively. Feature importance analysis revealed 'Weight', 'Gender', and 'CH2O' (water consumption) as the most significant predictors of obesity risk. SHAP value analysis provided deeper insights into the impact of these features across different obesity classes.

### Intellectual Merits and Practical Impacts
This project contributes to the field by providing a comprehensive analysis of obesity risk factors using cutting-edge machine learning techniques. The findings offer valuable insights for healthcare professionals and policymakers in developing targeted interventions for obesity prevention. Furthermore, the innovative methodology adopted in this study sets a new benchmark for future research in obesity prediction and other health-related fields.

