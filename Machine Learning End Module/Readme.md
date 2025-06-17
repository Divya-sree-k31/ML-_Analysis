Car Price Prediction - US Market Analysis
-------------------------------------------

Project Overview :
----------------
 A comprehensive machine learning analysis to help a Chinese automobile company understand pricing dynamics in the US market for their market entry strategy. This project implements and compares multiple regression algorithms to predict car prices and identify key factors affecting pricing in the American automotive market.

Business Objective :
--------------------
Primary Goal: Understand factors affecting car pricing in the American market to inform:

* Manufacturing unit setup decisions
* Local production strategies
* Competitive pricing against US and European manufacturers
* Product design and business strategy optimization

Dataset :
---------
* Source: Market survey data from American automobile market
* Size: Multiple car types and models across various price segments
* Features: 25+ attributes including technical specifications, design features, and performance metrics
* Target Variable: Car price in USD

Technical Implementation: 
-------------------------
Machine Learning Models Implemented

* Linear Regression - Baseline interpretable model
* Decision Tree Regressor - Non-linear relationships
* Random Forest Regressor - Ensemble method for robustness
* Gradient Boosting Regressor - Sequential error correction
* Support Vector Regressor - Non-linear kernel-based approach

Key Features:
--------------

1. Comprehensive Data Preprocessing
2. 5 Different ML Algorithms
3. Model Performance Comparison
4. Feature Importance Analysis
5. Hyperparameter Tuning
6. Business Insights & Recommendations

Project Structure:
------------------
car-price-prediction/
│
├── car_price_prediction.ipynb    # Main analysis notebook
├── README.md                     # This file
├── data/
│   └── car_data.csv             # Dataset (download required)
├── results/
│   ├── model_comparison.png     # Performance comparison charts
│   ├── feature_importance.png   # Feature importance plots
│   └── predictions_vs_actual.png # Model validation plots
└── requirements.txt             # Python dependencies

 Getting Started
 ----------------
Prerequisites
bashPython 3.8+
Jupyter Notebook
Required libraries (see requirements.txt)

Installation

1. Clone the repository
bashgit clone https://github.com/Divya-sree-k31/car-price-prediction.git
cd car-price-prediction

2. Install dependencies
bashpip install -r requirements.txt

3. Download the dataset
Download from: Google Drive Link
Save as data/car_data.csv

4.Run the analysis
bashjupyter notebook car_price_prediction.ipynb

Requirements:
-------------
Create a requirements.txt file with:

txtpandas>=1.3.0

numpy>=1.21.0

matplotlib>=3.4.0

seaborn>=0.11.0

scikit-learn>=1.0.0

jupyter>=1.0.0

Key Results:
------------
MODEL EVALUATION AND COMPARISON:

BEST PERFORMING MODEL

Best Model: Random Forest

R² Score: 0.9572


Model Evaluation Metrics:
-------------------------
R² Score: Measures explained variance (higher is better)

Mean Squared Error (MSE): Average squared prediction errors

Mean Absolute Error (MAE): Average absolute prediction errors

Root Mean Squared Error (RMSE): Square root of MSE

Hyperparameter Tuning:
---------------------
The project includes comprehensive hyperparameter optimization:

Grid Search Cross-Validation

5-Fold Cross-Validation

Performance Improvement Tracking

Optimal Parameter Selection

Contributing:
-------------
Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License:
------------
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments:
---------------
Dataset providers for comprehensive market data

Scikit-learn community for excellent ML tools

Open source contributors for supporting libraries







