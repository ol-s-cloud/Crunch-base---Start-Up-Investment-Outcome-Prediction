# Start-Up Investment Outcome Prediction

![Model Architecture](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/docs/images/model_architecture.svg)

A machine learning project that predicts startup IPO outcomes using ensemble methods and SHAP explanations. This research explores the transformative potential of machine learning and artificial intelligence in predicting the probability of a possible IPO using binary classification by analyzing key features from data provided by Crunchbase.

This research adopts an ensemble approach to model development, utilizing a combination of Logistic Regression, XGBoost, Random Forests, K-Nearest Neighbors and Neural Networks to make predictions alongside with SHapley Additive explanations (SHAP) to address the concerns of explainability and transparency and to justify the predictions. See experiment set up below:

![Experiment Set-up](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/Files/experiment-set-up.png)

## Key Takeaways

- **Data Source**: For research purposes, Crunchbase provided full apis access to data and thus was able to work with **Crunchbase data** to analyze key features influencing IPO outcomes -- PS: ONLY ON UK START-UPS and All data used for this research is updated as at: August 7, 2023. This date serves as the snapshot for the dataset used in the study.

 More Details on Crunchbase Data here - https://data.crunchbase.com/docs/getting-started
 
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

## Key Features

- Ensemble approach combining multiple ML models
- SHAP explanations for model interpretability
- Comprehensive startup data analysis
- High accuracy predictive capabilities
- Extensive feature engineering

##  Quick Start
(not sure you'd need this but just incase. For the full python repository and code version, I'll maybe be deploying that here on my spare time --- see: https://github.com/ol-s-cloud/start-up-inv-co-pilot)

**Note**: This research was primarily conducted using Orange Data Studio, an open-source machine learning and data visualization platform that played a crucial role in model development and analysis.

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

##  Model Performance

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

The outcome of the research suggests that of all the different models trained and tuned for this experiment, Gradient Boosting (XGBoost) performed the best with a 91.6% recall rate, minimizing false results while logistic regression was the least performing model with about 16.8% recall rate. Although SHAP is useful for explaining predictions and providing insights into individual predictions, it however does not imply causality. See the full research paper [here](https://raw.githubusercontent.com/ol-s-cloud/Start-Up-Investment-Outcome-Prediction/main/ML%20%26%20Data%20Science%20-%20IPO%20Vs%20Non-IPO%20Start%20up%20Outcome%20Prediction%20.pdf).

##  Research Roadmap

### Previous: Academic Research (2023)
- Master's dissertation research
- ML model development for IPO prediction
- Crunchbase data integration & analysis
- Ensemble model development & validation

### Current: start-up-inv-co-pilot (2024/2025) 
Open-source Python repository for startup investment analysis:

Full project here - https://github.com/ol-s-cloud/start-up-inv-co-pilot

1. **Core Features**
   - Automated data processing pipelines
   - Custom ML model implementations
   - Investment analysis tools
   - Performance visualization components

2. **API Integration**
   - Standardized data connectors
   - Multiple data source support
   - Real-time data processing
   - Customizable data pipelines

3. **Analysis Tools**
   - IPO prediction models
   - Risk assessment frameworks
   - Market trend analysis
   - Portfolio optimization

### Planned: Open Source Intelligence Platform (2025+)
Building a comprehensive startup intelligence ecosystem:

1. **Data Integration Hub**
   - Unified data schema
   - Multi-source synchronization
   - Real-time updates
   - Custom source integration

2. **Advanced Analytics Suite**
   - Deep learning models
   - Market intelligence
   - Predictive analytics
   - Risk modeling

3. **Collaborative Platform**
   - Community contributions
   - Model marketplace
   - Research sharing
   - Knowledge base

##  Research Collaboration

I'm open to research collaboration on:

1. **Research Topics**
   - ML in venture capital or other industrial applications
   - Startup success prediction
   - Market trend analysis
   - Risk assessment models

2. **Technical Projects**
   - Model development
   - Feature engineering
   - Data pipeline optimization
   - Visualization tools

3. **Academic Partnerships**
   - Joint research papers
   - Data sharing initiatives
   - Methodology development
   - Comparative studies

To collaborate or discuss research opportunities:
- 📧 Email: gs_wl8891@icloud.com
- 💻 GitHub: Create an issue or pull request

##  Current Ecosystem

### 1. Commercial Intelligence Platforms
- **Crunchbase** - Startup data & funding rounds
- **PitchBook** - Comprehensive financial data
- **Dealroom** - European startup intelligence
- **CB Insights** - AI-driven market insights

### 2. Open Source Alternatives (In Development)
- **Data Collection Framework**
  - Public data aggregation
  - API standardization
  - Data validation tools
  
- **Analysis Tools**
  - Market analysis scripts
  - Valuation models
  - Risk assessment frameworks

- **Visualization Components**
  - Interactive dashboards
  - Report generators
  - Trend visualizations

##  Further Reading

### Related Academic Research
1. [Finding the Unicorn: Predicting Early Stage Startup Success](https://www.researchgate.net/publication/325058611_Finding_the_Unicorn_Predicting_Early_Stage_Startup_Success_Through_a_Hybrid_Intelligence_Method) - Dellermann et al., 2021
2. [Machine Learning in Venture Capital](https://arxiv.org/abs/1606.04838) - Krishna et al., 2020
3. [Startup Success Prediction Using ML](https://www.researchgate.net/publication/328441510_Web-based_Startup_Success_Prediction) - Sharchilev et al., 2019

### Technical Resources
1. [SHAP Values in Machine Learning](https://github.com/ol-s-cloud/shap)
2. [Ensemble Methods for Prediction](https://scikit-learn.org/stable/modules/ensemble.html)
3. [Feature Engineering](https://en.wikipedia.org/wiki/Feature_engineering)
   
4. **Orange Data Studio**: An open-source machine learning platform used in this research. You can either download Orange or install Orange with pip

It is recommended to use a standalone installer or conda, You will need a C/C++ compiler (on Windows we suggest using Microsoft Visual Studio Build Tools). Orange needs PyQt to run. Install either:

PyQt5 and PyQtWebEngine: pip install -r requirements-pyqt.txt
PyQt6 and PyQt6-WebEngine: pip install PyQt6 PyQt6-WebEngine

Why Orange;

   - Comprehensive data mining and visualization tool
   - Supports wide range of machine learning algorithms
   - Key tool in developing and visualizing the startup IPO prediction models
   - 
- See: https://orangedatamining.com, https://github.com/biolab/orange3






### Industry Reports
1. [State of European Tech](https://www.stateofeuropeantech.com)
2. [Global Startup Ecosystem Report](https://startupgenome.com/)
3. [AI in Investment Decision Making - Delloitte ](https://www2.deloitte.com/content/dam/insights/articles/5075_CFS-AI-in-investment-decisions/DI_CFS-AI-in-investment-decisions.pdf)

## 🛠 Technical Details

For detailed technical specifications and model configurations, see:
- [Model Configurations](docs/MODEL_CONFIGURATIONS.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Code Documentation](docs/CODE_DOCUMENTATION.md)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐️ Citation

Said, O. (2023). A Comparative Study of Start Up Funding & The Use of Artificial Intelligence Powered by Machine Learning Algorithms to Predict Possible IPO vs Non-IPO Outcomes. Master's Dissertation, University of Stirling.

For BibTeX users:

```bibtex
@mastersthesis{said2023startup,
    title={A Comparative Study of Start Up Funding & The Use of 
           Artificial Intelligence Powered by Machine Learning Algorithms 
           to Predict Possible IPO vs Non-IPO Outcomes},
    author={Said, Olanrewaju},
    year={2023},
    school={University of Stirling}
}
```
