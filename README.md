# Titanic-Survival-Prediction
Predicting passenger survival using the classic Titanic dataset. This project implements a full Data Science pipeline: from EDA and data cleaning to feature engineering and Random Forest modeling. Key focus on identifying survival factors like class, age, and gender using Scikit-Learn.
Objectives
Perform Exploratory Data Analysis (EDA) to visualize survival trends.

Handle missing data and perform feature engineering (e.g., extracting insights from Age and Passenger Class).

Implement a Random Forest Classifier to predict outcomes.

Evaluate model performance using Confusion Matrices and Classification Reports.

Key Insights from EDA
The "Women and Children First" Rule: Gender was the strongest predictor of survival.

Socio-economic Impact: Passengers in 1st Class had a significantly higher survival probability compared to those in 3rd Class.

Age Dynamics: Children under 10 had higher survival rates, while males over 40 faced the lowest survival odds.

Technical Stack
Language: Python

Libraries:

Pandas & NumPy for data manipulation.

Matplotlib & Seaborn for data visualization.

Scikit-Learn for machine learning and model evaluation.

Model Performance
The final model was evaluated using a test split from the train.csv file.

Accuracy: ~82% (average)

Primary Features: Sex, Fare, and Pclass were identified as the most influential variables.

<img width="1115" height="653" alt="survival_factor_ss" src="https://github.com/user-attachments/assets/771512ba-a3e6-442c-aa9b-059f3279ed8b" />
