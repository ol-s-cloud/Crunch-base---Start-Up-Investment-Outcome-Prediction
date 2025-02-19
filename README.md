# Start-Up Investment Outcome Prediction

A machine learning project that predicts startup IPO outcomes using ensemble methods and SHAP explanations. This research explores the transformative potential of machine learning and artificial intelligence in predicting the probability of a possible IPO using binary classification by analyzing key features from Crunchbase data.

## 📊 Project Overview

This project implements an ensemble approach to model development, utilizing a combination of:
- Gradient Boosting (XGBoost)
- Random Forests
- Neural Networks
- K-Nearest Neighbors
- Logistic Regression

The models are trained on extensive startup data to predict IPO outcomes, with SHAP (SHapley Additive exPlanations) providing transparency and interpretability of predictions.

## 🎯 Key Results

Model performance metrics for the best performing model (Gradient Boosting):
- AUC: 0.993
- Correct Classification Rate: 0.996
- F1 Score: 0.954
- Precision: 0.996
- Recall: 0.916
- Matthews Correlation Coefficient: 0.953

## 🔧 Technical Architecture

### Data Processing Pipeline
1. Data Feature Engineering
2. Model Selection
3. Hyper-Parameter Tuning
4. Model Evaluation
5. ROC Analysis & Confusion Matrix
6. Predictions & SHAP Explanations

### Development Environment
- Primary Tool: Orange Data Mining Studio (Version 3.35.0)
- Data Processing: R-Studio with R-language
- Model Development: Orange Visual Programming

## 📋 Dataset Structure

The project utilizes multiple interconnected datasets from Crunchbase:

### Core Datasets
- **organizations.csv**: Central hub containing company profiles
- **funding_rounds.csv**: Funding event details
- **investors.csv**: Investor information
- **ipos.csv**: IPO event data
- **people.csv**: Individual profiles
- **jobs.csv**: Employment records

### Supporting Datasets
- category_groups.csv
- degrees.csv
- event_appearances.csv
- organization_descriptions.csv
- And more...

## 🎉 Features

Key features analyzed by the models include:
- Total Funding
- Raised Amount
- Job Types (especially Executive positions)
- Investment Counts
- Geographical Data
- Temporal Funding Patterns

## 🚀 Model Training

The data is split using a 60-20-20 ratio:
- 60% Training Data
- 20% Validation Data
- 20% Test Data

### Model Configurations

#### Gradient Boosting (XGBoost)
- Number of Trees: 100
- Learning Rate: 0.3
- Regularization Lambda: 1
- Max Tree Depth: 6

#### Random Forest
- Number of Trees: 10
- Minimum Split Size: 5

#### Neural Networks
Multiple configurations including:
- Hidden Layers: 5-10 neurons
- Activation Functions: ReLU, TanH, Identity
- Solvers: Adam, SGD, LBFGS-B

## 📈 Evaluation Metrics

The models are evaluated using:
- ROC Analysis
- Confusion Matrix
- Precision-Recall Metrics
- Matthews Correlation Coefficient

## 🔍 SHAP Analysis

SHAP values are used to explain individual predictions and feature importance. Key findings include:
- High impact of funding-related features
- Bidirectional impact of executive positions
- Moderate influence of gender and location

## 🌟 Future Improvements

Areas identified for future enhancement:
1. Integration of time series analysis for temporal patterns
2. Natural Language Processing for news and social media impact
3. Advanced feature engineering for funding patterns
4. Cloud computing integration for enhanced processing

## 🎓 Academic Context

This project was developed as part of a master's dissertation in finance & data analytics at the University of Stirling, focusing on predictive analytics in startup investments.

## 📄 License

This project uses data from Crunchbase under appropriate licensing and usage agreements. Please refer to Crunchbase's terms of service for data usage rights.

## 🤝 Acknowledgments

Special appreciation to:
- Crunchbase for providing the dataset
- University of Stirling for academic support
- Orange Data Mining team for their toolkit

## 📝 Citation

If you use this work in your research, please cite:
```
Said, O. (2023). A Comparative Study of Start Up Funding & The Use of 
Artificial Intelligence Powered by Machine Learning Algorithms 
to Predict Possible IPO vs Non-IPO Outcomes. Master's Dissertation, 
University of Stirling.
```

## 📞 Contact

For questions or collaborations, please contact:
- Email: olar.said@icloud.com
- Academic: ols00082@students.stir.ac.uk