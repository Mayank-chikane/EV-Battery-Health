# Project Title: Synthetic EV Battery Data Simulation and Predictive Modeling

### Project Description:
This project simulates synthetic data for electric vehicle (EV) batteries, focusing on key parameters such as the State of Health (SoH), State of Charge (SoC), Temperature, Voltage, and Current across 1000 charge-discharge cycles. The data is generated to mimic the behavior of EV batteries over time, providing a rich dataset for building predictive models to estimate the battery's State of Health (SoH).

## The project includes the following stages :
* Data Generation: Synthetic data for EV battery cycles is generated using random distributions for SoH, SoC, temperature, voltage, current, and cycle times.
* Data Preprocessing: Missing values are handled, outliers are detected and removed, and features are scaled (using Min-Max scaling and Standardization). Categorical features (if present) are encoded.
* Model Building and Training: A Linear Regression model and Random Forest Regressor are trained to predict the State of Health (SoH) based on the generated data.
* Model Evaluation: Performance metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-Squared (R²) are used to evaluate model performance. Hyperparameter tuning is performed to optimize the Random Forest model.
* Feature Importance Analysis: The importance of various features in predicting SoH is assessed using the Random Forest model’s feature importance.

## Key Features:
* Synthetic Data Generation: Simulated EV battery data for experimentation.
* Data Preprocessing Pipeline: Handling missing values, detecting outliers, and scaling features.
* Machine Learning Models: Linear Regression and Random Forest for predicting battery health.
* Model Evaluation: Performance metrics and cross-validation.
* Hyperparameter Tuning: Grid Search for optimizing the Random Forest model.
* Feature Importance: Identifying the most important features for model prediction.

## Technologies Used:

* Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
* Jupyter Notebooks for interactive data analysis and model building
* Git for version control

## Example Output:
* Plots of State of Health (SoH) over cycles
* Evaluation metrics for both the Linear Regression and Random Forest models
* Feature importance graph showing the significance of various battery parameters
