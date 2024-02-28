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

# Table of Contents

- [Literature](#Literature)
- [Method](#Method)
- [Data](#Data)
- [Code](#Code)
- [Results](#Results)
- [Spotlight](#spotlight)
- [More about the Author]
- [References]

## Literature

Our project builds upon existing research by integrating advanced machine learning techniques to predict obesity risk levels and identify key contributing factors. The literature review underscores the significance of utilizing large datasets and sophisticated algorithms to enhance obesity risk prediction accuracy.

## Method

We employed a comprehensive methodology that includes data preprocessing, feature selection, model training and evaluation, and hyperparameter optimization. Our approach combines ensemble machine learning techniques such as Random Forest, LightGBM, and XGBoost, augmented by SHAP values for feature importance evaluation.

## Data

The dataset was sourced from the "Multi-Class Prediction of Obesity Risk" competition on Kaggle, comprising features related to demographics, dietary habits, physical activity, and genetic factors. This rich dataset provided a solid foundation for our predictive models.

## Code

Our code includes scripts for data preprocessing, model training, hyperparameter tuning, and result visualization. These scripts are available in our GitHub repository, enabling reproducibility and further research.

## Results

The XGBoost model, optimized through extensive hyperparameter tuning, achieved the highest accuracy and F1-score, marking 'Weight', 'Gender', and 'CH2O' as the most critical predictors. SHAP analysis offered deeper insights into feature impact, enhancing our understanding of obesity risk factors.

## Spotlight


### Posters
- Poster presentations showcasing key findings and methodology.

![poster](spotlight/Stats201_Zhe_Niu_poster.png)
### Figures
- Visual representations of data distributions, model performance metrics, and feature importance scores.

![performance.png](spotlight/performance.png)


![feature_importance.png](spotlight/feature_importance.png)

![shap.png](spotlight/shap.png)

### Presentations

- Recorded presentations detailing our research process, findings, and future directions.

### Review articles
- References to review articles that have cited this work.

### Media appearance
- Mentions of this project in media outlets or press releases.

## More about the Author

### Headshot
![nz](nz.png)

### Self-introduction
- This project has significantly contributed to my understanding of machine learning applications in healthcare, particularly in predicting and analyzing obesity risk.


### Final reflections
- **Intellectual Growth:** Insights into how the project contributed to the author's knowledge expansion.
- **Professional Growth:** Discussion on professional skills developed through the project.
- **Living a Purposeful Life:** Reflections on how the project aligns with personal values and life goals.

## References

### Data Source

- **Data Source Title and URL:** "Multi-Class Prediction of Obesity Risk" [Kaggle Dataset](https://www.kaggle.com/competitions/multi-class-prediction-of-obesity-risk)

### Code Source

- **Code Source Title and URL:** GitHub Repository [Project Code](https://github.com/yourgithubusername/project-repository)

### Articles

- **Article Source Title and URL:** [Link to relevant article](#)

### Literature

#### Literature References in Chicago Author-Date Style and BibTex

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” The Review of Economics and Statistics 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```bibtex
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}

