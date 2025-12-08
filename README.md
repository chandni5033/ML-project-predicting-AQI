**Air Quality Index (AQI) Prediction and Analysis using Machine Learning**

This project focuses on predicting the Air Quality Index (AQI) using machine learning techniques.

We preprocess pollutant data, handle missing values, train multiple ML models, and compare their performance to determine the best AQI predictor.


**Project Overview**

Air pollution is a major problem in India, and AQI helps quantify how healthy or unhealthy the air is.

In this project, we:

Collected AQI-related pollutant data

Performed data cleaning and missing value imputation

Studied pollutant statistics (mean, median, distribution)

Trained multiple ML models for AQI prediction

Compared models using MAE, RMSE, and R² Score

Visualized the results


**Dataset Information**

The dataset contains pollutant values recorded from different Indian states.

Included Pollutants :

PM2.5

PM10

NO

NO₂

NOx

NH₃

SO₂

CO

O₃

Benzene, Toluene, Xylene 

Target Variable : AQI


**Data Preprocessing**

Steps performed

removed Xylene column (due to large missing values)

Checked missing values

Filled missing values using Median Imputation (Season-wise and State-wise for PM10 & NH3)

Encoded categorical columns


**Models Used**

Random Forest Regressor

Decision Tree Regressor


**Model Comparison**

We evaluated all models using:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score


**Tech Stack**

Python

Pandas

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook


**Clone the repository**

git clone https://github.com/<your-username>/<repo-name>.git


**Team Members**

Chandni

Ketki kuthe

Darshika Meharchandani


**Conclusion**

This project successfully demonstrates how machine learning can be used to predict AQI given pollutant data.
Among the models tested, Random Forest generally performed the best due to its ability to handle non-linear relationships and noise.
**Conclusion**
This project successfully demonstrates how machine learning can be used to predict AQI given pollutant data.
Among the models tested, Random Forest generally performed the best due to its ability to handle non-linear relationships and noise.
