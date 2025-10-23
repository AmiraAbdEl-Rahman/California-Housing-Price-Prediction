📋 Overview
Predicts California housing prices using the 1990 U.S. Census dataset with XGBoost algorithm.
Performance:

✅ Training R²: 94.37%
✅ Testing R²: 83.38%
✅ MAE: $31,086


📊 Dataset

Samples: 20,640
Features: 8 (MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude)
Target: Median house value (in $100,000s)
Source: Scikit-learn California Housing Dataset


🚀 Quick Start
Installation
bashpip install numpy pandas matplotlib seaborn scikit-learn xgboost
Usage
bashjupyter notebook House_Price.ipynb

🔬 Methodology

Data Loading - Load California Housing dataset
EDA - Correlation analysis, visualizations
Preprocessing - 80-20 train-test split
Model Training - XGBoost Regressor
Evaluation - R² Score, MAE metrics


📈 Results
MetricTrainingTestingR² Score94.37%83.38%MAE$19,336$31,086
Key Insight: Median Income shows strongest correlation (0.69) with house prices.

💻 Tech Stack

Python 3.8+
Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost
Environment: Jupyter Notebook / Google Colab


🔮 Future Work

 Hyperparameter tuning
 Feature engineering
 Deploy as REST API
 Web interface


🤝 Contributing

Fork the repo
Create feature branch (git checkout -b feature/NewFeature)
Commit changes (git commit -m 'Add NewFeature')
Push to branch (git push origin feature/NewFeature)
Open Pull Request
