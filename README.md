# Start-Up Investment Outcome Prediction

![Model Architecture](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/docs/images/model_architecture.svg)

A machine learning project that predicts startup IPO outcomes using ensemble methods and SHAP explanations. This research explores the transformative potential of machine learning and artificial intelligence in predicting the probability of a possible IPO using binary classification by analyzing key features from data provided by Crunchbase.

In this research we adopt an ensemble approach to model development, utilizing a combination of Logistic Regression, XGBoost, Random Forests, K-Nearest Neighbors and Neural Networks to make predictions alongside with SHapley Additive explanations (SHAP) to address the concerns of explainability and transparency and to justify the predictions. See experiment set up below:

![Experiment Set-up](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/Files/experiment-set-up.png)

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

## 🚀 Quick Start
(not sure you'd need this but just incase. For the full python repository and code version, see: https://github.com/ol-s-cloud/start-up-inv-co-pilot)

```bash
# Clone the repository
git clone https://github.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction.git

# Set up environment
python -m venv venv
source venv/bin/activate  # Unix
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Run sample prediction
python src/predict.py --sample data/example.csv
```

## 📊 Model Performance

Results from the ensemble models:

| Metric | Score |
|--------|--------|
| AUC | 0.993 |
| Accuracy | 0.996 |
| F1 Score | 0.954 |
| Precision | 0.996 |
| Recall | 0.916 |

![Model Performance](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/docs/images/performance.svg)

## ROC Analysis Curve 
![ROC Analysis Curve](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/Files/ROC%20Analysis%20Curve.png)

The outcome of the research suggests that of all the different models trained and tuned for this experiment, Gradient Boosting (XGBoost) performed the best with a 91.6% recall rate, minimizing false results while logistic regression was the least performing model with about 16.8% recall rate. Although SHAP is useful for explaining predictions and providing insights into individual predictions, it however does not imply causality. see full research here - (https://raw.githubusercontent.com/ol-s-cloud/main/ML%20%26%20Data%20Science%20-%20IPO%20Vs%20Non-IPO%20Start%20up%20Outcome%20Prediction%20.pdf)

[Rest of the README remains the same...]