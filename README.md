# Project Title
Forecasting Electric Vehicle Adoption Using Machine Learning

# Executive Summary
Future electric vehicle (EV) adoption can be forecast by analyzing historical EV sales trends alongside the current number of EVs on the road. Historical sales data reveal how rapidly EV adoption has grown and how consumers have responded to improvements in technology, pricing, and government incentives. The current EV population reflects market acceptance and progress toward widespread adoption. When combined, these data provide a strong foundation for projecting future EV growth and support informed planning by policymakers, businesses, and utilities for charging infrastructure, energy demand, and long-term transportation needs.

# Rationale
Understanding future EV adoption is critical for effective planning and investment. Automakers need reliable forecasts to scale production, utilities must anticipate changes in electricity demand, and city planners must determine where and when charging infrastructure should be deployed. Poor forecasts could result in overinvestment, wasted resources, or infrastructure shortages that slow adoption.

This analysis transforms historical data into actionable insights about future EV demand. By using data-driven methods, the project supports better decision-making, more efficient allocation of resources, and a smoother transition to electric transportation.

# Research Question
How can historical EV sales patterns and the current EV population be used to forecast future electric vehicle adoption in the United States using machine learning techniques?

# Data Sources
https://www.kaggle.com/datasets/jainaru/electric-car-sales-2010-2024

# Methodology
Linear regression, Polynomial regression, Trend Analysis

# Results
<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/1a5d9a31-9318-476c-a000-aa119a16c037" />
<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/379de6c3-cc26-43b5-b35f-a67be8dc3a99" />
<img width="576" height="453" alt="image" src="https://github.com/user-attachments/assets/1b7bb08c-7ba5-4f0b-a19c-96001e5228c7" />
<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/ba0b62c5-ae05-4830-b09f-f45f00c39c17" />
The visual EDA shows that global EV adoption follows a clear diffusion pattern. EV sales grow slowly in the early years and accelerate sharply after 2019, while EV stock increases smoothly and rapidly as a cumulative measure of adoption. The widening gap between sales and stock reflects the accumulation effect typical of new technologies. Overall, the trends indicate that EVs have transitioned from an early adoption phase to a rapid growth phase globally.

<img width="579" height="453" alt="image" src="https://github.com/user-attachments/assets/d38d2f76-0457-48fc-ba8d-c07e1955901f" />
The graph shows that while the linear regression captures the general upward trend in EV sales, it does not fit the data well. It performs poorly in the early years and fails to capture the rapid growth in later years, indicating that EV sales grow in a nonlinear pattern rather than a linear one.

<img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/9ac383d9-8a47-47a6-8778-bc7d294b645f" />
The graph shows that polynomial regression fits EV sales much better than linear. It shows a slow early growth and rapid increase in recent years, showing that EV sales grow in a nonlinear way.

<img width="569" height="453" alt="image" src="https://github.com/user-attachments/assets/7b54361e-b68d-4bb2-9a27-3f1d62a7c0c6" />
The graph shows historical global EV sales along with a polynomial regression fit and a forecast for 2027. EV sales grow slowly in the early years and then accelerate sharply after 2018, indicating a nonlinear adoption pattern. The fitted curve closely follows the historical data, capturing this acceleration well. Based on the extrapolated trend, global EV sales are projected to increase substantially by 2027, reaching a much higher level than recent years. This suggests continued rapid expansion of the EV market, assuming current growth dynamics persist.

# Next steps
Repeat the analysis for major markets (e.g., US, China, EU).
Use GridSearchCV for SVR or Decision Tree and compare results with polynomial regression

# Outline of project
https://github.com/apandey2015/Initial-Project-Report-EDA/blob/main/Initial%20Project%20Report%20EDA.ipynb
