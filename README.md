# ✈️ ACCIDENT TREND FORECASTING
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-006699?logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-2E8B57)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-F7931E?logo=scikitlearn&logoColor=white)
![ARIMA](https://img.shields.io/badge/ARIMA-Time%20Series-ff6f61)
![Prophet](https://img.shields.io/badge/Prophet-Forecasting-1abc9c)
![Forecasting](https://img.shields.io/badge/Forecasting-Time%20Series-F39C12)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab&logoColor=white)
![License](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)

**Forecasting the yearly number of aviation accidents (1962–2022) using ARIMA and Prophet models.**

Prophet was selected as the best-performing model based on forecast accuracy.

---
## **📌 Project Purpose**

This project analyzes historical aviation accident data to identify long-term trends and forecast future yearly accident counts. Insights from this analysis support aviation safety evaluation and policy planning.

## **🎯 Objectives**

1. Understand historical trends in aviation accidents

2. Forecast future yearly accident counts

3. Compare time-series models (ARIMA, Prophet)

4. Identify the best model for reliable forecasts

---

## **🗂 Dataset**

Source: **NTSB Aviation Accident Dataset (1962–2022)**

Preprocessing:

1. Filtered relevant records

2. Aggregated accidents by year

3. Handled missing or inconsistent values

---

## **📈 Exploratory Data Analysis (EDA)**

**Key observations:**

- Long-term fluctuations in yearly accident counts

- Peaks and declines correlate with industry regulation and technological changes

- COVID-19 caused a noticeable dip in 2020

---

### **📊 Visualization:**

**Yearly aviation accident trends**

<img width="984" height="584" alt="image" src="https://github.com/user-attachments/assets/fbe4740c-79b9-49f2-b420-4e0416a1ce8c" />

**Monthly aviation accident count**

<img width="984" height="584" alt="image" src="https://github.com/user-attachments/assets/51221dd1-74e1-4ba6-b3db-8c513e81b085" />

---

**Tableau interactive dashboard**

<img width="1181" height="511" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/4fd2cc56-fe36-45ab-9657-65bbc1b03d50" />

Link : https://public.tableau.com/app/profile/kenneth.nyangweso/viz/PHASEPROJECTINTERACTIVEDASHBOARD/DSFPH1DASHBOARD

---
## **🧠 Forecasting Models**

**Models implemented:**

- ARIMA

- Prophet (best-performing)

**Evaluation metrics:**

1. Mean Absolute Error (MAE)

2. Root Mean Squared Error (RMSE)

Key Insight: Prophet produced the most reliable forecasts and captured long-term trends effectively.

## **📊 Results**

**Prophet Forecast (2023–2027)**

<img width="983" height="583" alt="image" src="https://github.com/user-attachments/assets/2d3c76f6-7ab8-4fb0-81a4-3624b912d519" />

- Forecast indicates a continued gradual decline in yearly accidents

- Confidence intervals account for potential variability in future trends

---

### **Model Comparison**

    
| Model  | MAE    | RMSE   |
|--------|--------|--------|
| ARIMA  | 89.21  | 112.48 |
| Prophet| 79.96  | 100.41 |

---

# **🛠 Tools & Technologies**

1. Python - programming language

2. Pandas, NumPy – data handling

3. Matplotlib, Seaborn – visualization

4. Statsmodels – ARIMA & SARIMA

5. Facebook Prophet – time-series forecasting

---

## **📥 How to Use / Run**

1. Clone the repo

       git clone https://github.com/kennethnyangweso/Aviation-Accident-Trend-Forecasting.git

2. Install dependencies

       pip install -r requirements.txt
 
3. Run / explore notebooks

- Open DSF_PHASE_1_Project...ipynb in Jupyter to explore EDA and modeling.

---

## **🔮 Future Improvements**

1. Include per-flight accident rates to normalize for flight volume

2. Integrate external variables (weather, regulations) for improved forecasting

3. Explore LSTM or other deep learning models for time-series prediction

---

## **👤 Author**

**Kenneth Nyangweso**

**Data Scientist | Electrical & Telecommunications Engineer**

