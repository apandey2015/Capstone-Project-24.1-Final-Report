**Problem Statement**
The objective of this study is to analyze and forecast global electric vehicle (EV) adoption using machine learning methods. EV adoption has increased rapidly in recent years due to better technology, lower costs, and supportive environmental policies. However, this growth is non-linear, which makes traditional linear forecasting models less accurate.
The main challenge is to identify which machine learning models can best capture this accelerating adoption trend and provide reliable future forecasts. Accurate EV sales forecasts are important for planning, infrastructure development, energy management, and investment decisions. Therefore, this study evaluates several regression and classification models to determine the most suitable approach for long-term EV adoption forecasting.



**Model Outcomes and Predictions**
This project uses supervised learning because historical EV data with known outcomes is available. Two tasks were performed: regression and classification.
Regression was used to predict future global EV sales. The models used were Linear Regression, Polynomial Regression, KNN Regressor, and Decision Tree Regressor.
Classification was used to label EV adoption as above or below the median. The models used were Logistic Regression, KNN, Decision Tree, and SVM.



**Data Acquisition**
The dataset was compiled from global EV statistics, containing EV sales, EV stock, EV sales share, EV stock share. The data spans multiple years (2010–2023) and includes global and regional observations. Using multiple indicators allows the model to capture both adoption levels and growth dynamics.
The outputs are future EV sales forecasts and binary adoption labels.
Data Sources: https://www.kaggle.com/datasets/jainaru/electric-car-sales-2010-2024



**Data Preprocessing/Preparation**
Missing values were identified and removed, duplicate records were deleted, and measurement units were standardized. The data was split into 80% training and 20% testing sets using a fixed random seed to ensure consistent results. Categorical variables were encoded as needed, and numerical features were scaled for models such as KNN and SVM. Feature processing focused on capturing year-based trends and EV adoption patterns.



**Modeling**
Based on the problem, several regression and classification models were selected. For regression, the models used were Linear Regression, Polynomial Regression, KNN Regressor, and Decision Tree Regressor.
For classification, the models used were Logistic Regression, KNN, Decision Tree, and SVM. Using multiple models allowed comparison of accuracy, interpretability, and forecasting performance.



**Model Evaluation**
Regression models were evaluated based on how well they captured trends and future growth, while classification models were evaluated on their ability to distinguish high and low EV adoption.
Performance was measured using visual trend analysis for regression and accuracy, ROC-AUC, and confusion matrices for classification.



**Results**
Polynomial Regression performed best for long-term EV sales forecasting because it captured accelerating growth. Linear Regression underestimated future growth, while KNN and Decision Tree regressors produced flat forecasts.
For classification, the tuned SVM achieved the highest ROC-AUC, with Logistic Regression offering the best balance between performance and interpretability.



**Next Steps**
Repeat the analysis for major markets (e.g., US, China, EU).


**Outline of the project**
Initial: https://github.com/apandey2015/Initial-Project-Report-EDA/blob/main/Initial%20Project%20Report%20EDA.ipynb

Final: 

