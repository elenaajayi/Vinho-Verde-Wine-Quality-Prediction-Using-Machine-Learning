# Vinho-Verde-Wine-Quality-Prediction-Using-Machine-Learning

**Overview:**
This project leverages advanced machine learning algorithms to predict the quality of Vinho Verde wine based on its physicochemical properties. We employ a Gradient Boosting Regressor model optimized using Bayesian optimization techniques to improve accuracy, evaluated by Mean Squared Error (MSE).


**Key Features**
Wine Dataset: 4,750 samples with 12 physicochemical attributes.
Modeling Techniques: Gradient Boosting Regressor optimized via Bayesian methods.
Performance Metric: Mean Squared Error (MSE) used to evaluate model accuracy.

**Methodology**
Data Preprocessing:
Standardization of features using StandardScaler.
Handling of outliers through visual inspection (box plots) and necessary corrections.
Feature transformations using PolynomialFeatures and PowerTransformer to improve normality.
Model Optimization:

Bayesian Optimization through BayesSearchCV to fine-tune hyperparameters.
Key parameters tuned: learning rate, tree depth, number of trees, and subsample rate.

**Results:**
The optimized model achieved an MSE of 0.266, improving over previous iterations but still above the target of 0.10.
The project identified alcohol and acidity as critical factors influencing wine quality.

**Next Steps:**
Explore further model fine-tuning and feature engineering to lower the MSE.
Experiment with other machine learning models or deep learning techniques.
To improve accuracy, integrate additional data types (e.g., sensory or weather data).

**References:**
Cortez, P., et al. (2009). "Modeling wine preferences by data mining from physicochemical properties." Decision Support Systems, 47(4), 547-553.
Jones, D., et al. (2015). "Predictive modeling for wine quality: A comparative approach." Journal of Wine Research, 26(3), 123-137.
