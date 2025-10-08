# Forecasting Headline Inflation with Hybrid Time Series Models

## 📘 Overview
This project focuses on **forecasting India’s headline inflation** using a combination of **statistical** and **machine learning–based hybrid time series models**. The motivation stems from the growing importance of accurate inflation forecasting in guiding monetary policy decisions and improving economic planning — especially for institutions like the **Reserve Bank of India (RBI)**.

The project integrates classical econometric approaches such as **ARIMA** and **Prophet** with modern **deep learning models** like **LSTM**, leveraging their complementary strengths to improve forecasting accuracy and interpretability.

---

## 🎯 Objectives
- To model and forecast India’s **headline inflation rate** using hybrid time series frameworks.  
- To compare model performance between **pure statistical**, **machine learning**, and **hybrid** models.  
- To evaluate accuracy using performance metrics such as **RMSE**, **MAE**, and **MAPE**.  
- To visualize the inflation trends and generate future forecasts.

---

## 🧩 Methodology
### 1. Data Collection
- **Source:** Official inflation data from the **Reserve Bank of India (RBI)** and **MOSPI**.  
- **Frequency:** Monthly data.  
- **Period Covered:** Historical data spanning multiple years (up to 2025).  

### 2. Data Preprocessing
- Handling missing values and outliers.  
- Log transformation and differencing to achieve stationarity.  
- Train–test split for out-of-sample evaluation.

### 3. Model Development
- **Statistical Models:** ARIMA, SARIMA  
- **Machine Learning Models:** LSTM, Prophet  
- **Hybrid Models:**  
  - **ARIMA–LSTM:** Captures both linear (ARIMA) and nonlinear (LSTM) patterns.  
  - **ARIMA–Prophet:** Combines seasonality handling of Prophet with ARIMA residual learning.  

### 4. Evaluation Metrics
- **Root Mean Square Error (RMSE)**  
- **Mean Absolute Percentage Error (MAPE)**  
- **R² Score**

### 5. Visualization
- Time series decomposition plots.  
- Model fit and residual diagnostics.  
- Actual vs. predicted inflation trends.  
- Future inflation forecasts.

---

## 📊 Results & Insights
- Hybrid models, especially **ARIMA–LSTM**, outperformed standalone models in both short-term and medium-term forecasts.  
- The hybrid framework effectively captured inflation shocks and seasonal effects.  
- The study demonstrates that integrating deep learning into traditional econometric pipelines can significantly enhance forecasting accuracy for macroeconomic indicators.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  - Data Handling: `pandas`, `numpy`  
  - Time Series Modeling: `statsmodels`, `fbprophet`, `pmdarima`  
  - Machine Learning / Deep Learning: `scikit-learn`, `tensorflow`, `keras`  
  - Visualization: `matplotlib`, `seaborn`, `plotly`

---

## 📁 Project Structure
