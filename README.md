# ML-Miniproject

Based on the paper: Healthy Life Expectancy (HALE) Analysis and Prediction using Machine Learning
https://ieeexplore.ieee.org/document/10987496
Authors: Pranjal T S, Srijan Badhya, Neha Reddy, Srikrishna B, Priya Badrinath CSE Department, PES University, Bangalore, India 


# Abstract 
This project predicts Healthy Life Expectancy at age 60 (HALE_60) using WHO Global Health Observatory data from 185 countries spanning 2000 to 2019, by applying machine learning on socio-economic and health indicators such as adult mortality, obesity, and physical inactivity. Existing studies largely focus on general life expectancy using linear models, which fail to capture the complex, non-linear relationships between health variables, leaving a gap in accurate HALE specific prediction. To address this, a multi-model machine learning framework is proposed that compares both linear and ensemble methods to identify the most impactful predictors of healthy aging. The dataset of 3,700 records was preprocessed using median imputation and log normalization, then used to train eight models (Linear Regression, Ridge, Lasso, Random Forest, Gradient Boosting, AdaBoost,KNN and SVR) evaluated using MSE and R². Ensemble models outperformed all others, with Random Forest achieving the best results (MSE: 0.004, R²: 0.9954), and Infant Mortality Rate emerging as the most significant predictor. This system can assist governments and health organizations in identifying high-risk regions and making data-driven decisions to improve healthy aging outcomes globally. 
