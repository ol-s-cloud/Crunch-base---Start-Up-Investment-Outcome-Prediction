# Start-Up Investment Outcome Prediction

![Model Architecture](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/docs/images/model_architecture.svg)

A machine learning project that predicts startup IPO outcomes using ensemble methods and SHAP explanations. This research explores the transformative potential of machine learning and artificial intelligence in predicting the probability of a possible IPO using binary classification by analyzing key features from data provided by Crunchbase.

In this research we adopt an ensemble approach to model development, utilizing a combination of Logistic Regression, XGBoost, Random Forests, K-Nearest Neighbors and Neural Networks to make predictions alongside with SHapley Additive explanations (SHAP) to address the concerns of explainability and transparency and to justify the predictions. See experiment set up below:

![Experiment Set-up](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/Files/experiment-set-up.png)

## 🎯 Key Takeaways:
• The research uses **Crunchbase data** to analyze key features that influence IPO outcomes.
• The study employs **multiple machine learning models,** including **Logistic Regression, XGBoost, Random Forests, K-Nearest Neighbors, and Neural Networks.**
• **XGBoost performed the best** with a **91.6% recall rate**, while **Logistic Regression had the weakest recall at 16.8%.**
• **SHapley Additive Explanations (SHAP)** is used to interpret and explain model predictions.
• Ethical considerations include **removing personal information** and avoiding **look-ahead bias.**
• The study is focused on **UK-based start-ups** from **1999-2020.**
• **Future recommendations** include integrating **time-series analysis** and **natural language processing (NLP)** for behavioral factors.

## Crunchbase Entity Relationship
![Crunchbase Entity Relationship](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/Files/crunchbase%20entity%20relationship.png)

<p align="center">
<a href="#-key-features">Key Features</a> •
<a href="#-quick-start">Quick Start</a> •
<a href="#-model-performance">Performance</a> •
<a href="#-research-roadmap">Roadmap</a> •
<a href="#-ecosystem">Ecosystem</a> •
<a href="#-further-reading">Further Reading</a>
</p>

## 🎯 Key Features

- Ensemble approach combining multiple ML models
- SHAP explanations for model interpretability
- Comprehensive startup data analysis
- High accuracy predictive capabilities
- Extensive feature engineering

[Rest of the README remains the same...]