Car Price Prediction Using Machine Learning (Real-World Inaccurate Data)

Project Overview:-

Car price prediction is a common regression problem in machine learning that aims to estimate the selling price of a car based on its features.
In real-world scenarios, datasets are often incomplete, noisy, and inaccurate due to missing values, inconsistent entries, and human errors.

This project focuses on building a robust car price prediction model that can handle inaccurate and imperfect data using effective preprocessing techniques and supervised learning algorithms.

Objectives:-

Predict car prices using historical and feature-based data
Handle missing values, outliers, and noisy data
Compare multiple regression models
Evaluate performance using standard error metrics
Improve prediction accuracy through feature engineering

Dataset Description:-

The dataset contains various car-related attributes such as:
Brand
Model
Year of Manufacture
Fuel Type
Transmission Type
Mileage
Engine Capacity
Owner Count
Selling Price (Target Variable)


Note:-

The dataset is intentionally imperfect and contains:
Missing values
Outliers
Inconsistent formats
Noisy numerical values
This helps simulate real-world prediction challenges.


Data Preprocessing:-

To improve model reliability, the following preprocessing steps were applied:
Handling missing values (mean/median/imputation)
Removing or treating outliers
Encoding categorical variables
Feature scaling using MinMaxScaler / StandardScaler
Train-test split for evaluation


Machine Learning Models Used:-

Linear Regression
Gradient Boosting Regressor


Evaluation Metrics:-

Model performance was evaluated using:
Root Mean Squared Error (RMSE)

This metrics help assess how well the model performs on inaccurate real-world data.


Results & Insights:-

Ensemble models performed better on noisy data
Feature engineering significantly improved accuracy
Outliers had a strong impact on linear models
Proper preprocessing reduced error rates substantially


Technologies Used:-

Python
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
Google Collab Notebook



📂 Project Structure
├── data/
│   └── car_data.csv
├── notebooks/
│   └── car_price_prediction.ipynb
├── README.md


Conclusion:-

This project demonstrates how machine learning models can be trained effectively even when working with inaccurate and noisy datasets, which is a common challenge in real-world applications.
It highlights the importance of preprocessing, evaluation, and model selection in building reliable prediction systems.
