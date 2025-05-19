
## *HARNESSING AI-DRIVEN PREDICTIONS OF TOTAL ELECTRON CONTENT IN IONOSPHERE*

## *Overview*

This project focuses on predicting *Total Electron Content (TEC)* variations in the ionosphere caused by *solar flares, solar storms, and **earthquakes. Using machine learning models like **Random Forest Regressor* and *XGBoost*, we aim to analyze the impact of space weather and seismic events on space-based navigation systems.

---

## *Table of Contents*

1. Project Description
2. Data Sources
3. Technologies and Methodologies used
4. Key Parameters
5. Event Windows(2024)
6. Model Training
7. Results Summary
8. Dependencies

---

## *Project Description*

To develop a robust model that predicts TEC fluctuations during significant solar and seismic events using real observational data and multiple ML algorithms, and to assess their performance against standard models like *IRI 2020*.


---

## *Data Sources*

- *INONO Lab* – Real TEC observations  
- *IRI 2020 Model* – Standard ionospheric model  
- *OMNIWeb (NASA)* – Geomagnetic and solar parameters  

---

## *🔧 Technologies and Methodologies Used*

- *Languages & Tools:* Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost
- *ML Algorithms:* Random Forest Regressor, XGBoost Regressor
- *Evaluation Metrics:* R² Score, MSLE, SMAPE, MAE, RMSE


---

## *🔍 Key Parameters*

- *Solar & Geomagnetic Parameters:*  
  - SSN (Sunspot Number)  
  - Kp Index  
  - Ap Index  
  - F10.7 cm Solar Flux  
- *Target Variable:* True TEC values (from INONO)

---

## *📅 Event Windows (2024)*

- *Solar Flares:* Feb 22 (X6.7), May 14 (X8.79)
- *Solar Storms:* May 6–17, Oct 6–15
- *Earthquakes:* Jan 1, 2024 and Oct 26, 2013

---

## *🧠 Model Training*

- *Training Period:* 2023–2024
- *Comparison:* Model predictions vs true TEC vs IRI 2020 outputs

---

## *📈 Results Summary*

-The models successfully captured TEC fluctuations during major solar and seismic events in 2024.

-The predicted TEC values closely aligned with true measurements and provided noticeable improvements over the IRI 2020 model in dynamic conditions.

-These results highlight the potential of machine learning in enhancing the reliability of ionospheric predictions for navigation and communication systems.

---

## *Dependencies*

* Python 3.x
* Libraries:

  * pandas
  * numpy
  * matplotlib, seaborn
  * scikit-learn
  * xgboost

