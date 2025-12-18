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

<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/5ad2c43e-77e1-4a7a-87fb-160f1a291fbc" />
The figure highlights the rapid and reinforcing growth of both annual EV sales and the total EV stock over time. While EV sales increase steadily, the cumulative EV stock grows much faster, reflecting the compounding effect of year-on-year adoption. The widening gap between stock and sales after 2018 indicates that EVs are not only being sold at higher rates but are also remaining in use, leading to a rapidly expanding installed base. Overall, the chart confirms that the global EV market has moved into a self-sustaining scale-up phase, where rising sales continuously feed into an accelerating stock of electric vehicles, strengthening long-term adoption momentum.

<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/9d925d34-fb39-41d2-a783-38e3cccef77f" />
The graph shows that polynomial regression fits EV sales much better than linear regression. It captures the slow early growth and the rapid increase in recent years, showing that EV sales grow in a nonlinear way.

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/8a7b9e38-035b-4719-939c-1fc3129c3075" />
The figure shows a clear upward trend in global EV sales, with slow adoption in the early 2010s followed by rapid acceleration after 2018. This shift reflects improvements in EV technology and stronger policy support. The polynomial regression closely follows the observed pattern and projects continued strong growth through 2030, with EV sales rising sharply each year. Overall, the graph indicates that EV adoption is accelerating and is better captured by non-linear models than by simple linear trends.

<img width="691" height="545" alt="image" src="https://github.com/user-attachments/assets/adfd5f95-740a-42f0-baa0-c5b317e4abba" />
ROC curve indicates that all models perform well, with Logistic Regression and SVM achieving the highest accuracy. KNN performs nearly as well, while the Decision Tree is slightly weaker. Overall, Logistic Regression provides the best balance of performance and interpretability for classifying EV adoption levels.

<img width="889" height="490" alt="image" src="https://github.com/user-attachments/assets/e0695ba2-9eb3-4160-8388-a02f4e5507dc" />
The forecast visualization shows that Linear Regression predicts continued growth through 2030, while KNN and Decision Tree regressors provide more conservative, stable projections. These differences reflect each model’s ability to extrapolate trends, emphasizing the importance of using multiple models when forecasting future values.

<img width="768" height="468" alt="image" src="https://github.com/user-attachments/assets/030bd5e4-f83c-42f0-ad6b-552669c1441d" />
Hyperparameter tuning significantly improved model performance, with the most dramatic gains observed for SVM and Decision Tree models. While Logistic Regression and KNN showed modest improvements, the tuned SVM achieved the highest overall ROC-AUC, demonstrating the critical importance of tuning for complex models. These results highlight that default settings may be sufficient for simpler algorithms, but advanced models require careful optimization to reach their full potential.

**Summary**
This study applied multiple regression and classification models to forecast electric vehicle adoption and evaluate their predictive suitability. Among all models tested, Polynomial Regression emerged as the most appropriate predictive model for long-term EV sales forecasting. It effectively captures the accelerating nature of EV adoption, extrapolates reliably beyond historical data, and balances predictive realism with interpretability. In contrast, KNN and Decision Tree models were limited to historical patterns and produced flat forecasts, while Linear Regression underestimated future growth by assuming constant trends. Overall, Polynomial Regression provides the most defensible and practical framework for forecasting future EV adoption and supporting informed planning and policy decisions.








**Next Steps**
Repeat the analysis for major markets (e.g., US, China, EU).


**Outline of the project**
Initial: https://github.com/apandey2015/Initial-Project-Report-EDA/blob/main/Initial%20Project%20Report%20EDA.ipynb

Final: https://github.com/apandey2015/Capstone-Project-24.1-Final-Report/blob/main/Final-Capstone-Project.ipynb

