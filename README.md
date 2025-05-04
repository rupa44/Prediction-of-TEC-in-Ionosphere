

## **HARNESSING AI-DRIVEN PREDICTIONS OF TOTAL ELECTRON CONTENT IN IONOSPHERE**

## **Overview**

This project focuses on forecasting Total Electron Content (TEC) using machine learning models trained on space weather data. Accurate TEC prediction is essential for maintaining the reliability of satellite communication and navigation systems. The objective is to build predictive models using geomagnetic indices and solar activity parameters.

---

## **Table of Contents**

1. Project Description
2. Dataset
3. Preprocessing
4. Feature Engineering
5. Model Development
6. Evaluation
7. Visualization
8. Dependencies

---

## **Project Description**

The ionosphere influences GPS and satellite signals, especially during geomagnetic disturbances. This project uses historical TEC data and parameters like Kp, Ap, SSN, and F10.7 to build time series regression models. These models are used to forecast TEC values 24 hours in advance.

---

## **Dataset**

The dataset includes:

* **Target variable**: Total Electron Content (TEC)
* **Features**:

  * Kp index (planetary K index)
  * Ap index (planetary amplitude index)
  * SSN (Sunspot Number)
  * F10.7 (Solar Radio Flux)
  * IRI TEC (from the IRI 2020 model)

Data collected from sources like NASA OMNIWeb and NOAA for the year 2023.

---

## **Preprocessing**

* Handling missing values and aligning timestamps
* Normalization of features
* Date-wise slicing of training data for time-series model integrity

---

## **Feature Engineering**

* Polynomial feature expansion (degree = 2)
* Scaling using StandardScaler
* Time-sliced training sets based on prediction date

---

## **Model Development**

The models used in this project include:

* **Random Forest Regressor**
* **XGBoost Regressor**

Each model is trained daily using data before the prediction date to maintain real-time forecasting integrity.

---

## **Evaluation**

Evaluation metrics used for performance assessment:

* **R² Score**
* **Adjusted R²**
* **Root Mean Squared Error (RMSE)**
* **Residual Sum of Squares (RSS)**

Results compared against IRI 2020 predicted TEC values.

---

## **Visualization**

* Scatter plots comparing true vs. predicted TEC
* Regression line overlay
* Evaluation statistics box (intercept, slope, R², etc.)

---

## **Dependencies**

* Python 3.x
* Libraries:

  * `pandas`
  * `numpy`
  * `matplotlib`, `seaborn`
  * `scikit-learn`
  * `xgboost`

