# Start-Up Investment Outcome Prediction

![Model Architecture](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/docs/images/model_architecture.svg)

A machine learning project that predicts startup IPO outcomes using ensemble methods and SHAP explanations. This research explores the transformative potential of machine learning and artificial intelligence in predicting the probability of a possible IPO using binary classification by analyzing key features from data provided by Crunchbase.

In this research we adopt an ensemble approach to model development, utilizing a combination of Logistic Regression, XGBoost, Random Forests, K-Nearest Neighbors and Neural Networks to make predictions alongside with SHapley Additive explanations (SHAP) to address the concerns of explainability and transparency and to justify the predictions. See experiment set up below:

![Experiment Set-up](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/Files/experiment-set-up.png)

## 🎯 Key Takeaways

- **Data Source**: Utilized **Crunchbase data** to analyze key features influencing IPO outcomes
- **Machine Learning Models**: Employed multiple models including:
  * Logistic Regression
  * XGBoost
  * Random Forests
  * K-Nearest Neighbors
  * Neural Networks
- **Model Performance**: 
  * **XGBoost** performed best with a **91.6% recall rate**
  * **Logistic Regression** had the weakest recall at **16.8%**
- **Interpretability**: Used **SHapley Additive Explanations (SHAP)** to interpret and explain model predictions
- **Ethical Considerations**: 
  * Removed personal information
  * Avoided look-ahead bias
- **Research Scope**: 
  * Focused on **UK-based start-ups**
  * Analyzed data from **1999-2020**
- **Future Recommendations**: 
  * Integrate **time-series analysis**
  * Incorporate **natural language processing (NLP)** for behavioral factors

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

[Rest of the README remains the same...]