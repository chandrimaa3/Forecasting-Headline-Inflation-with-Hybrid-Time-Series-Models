# Forecasting Headline Inflation with Hybrid Time Series Models

## 📘 Overview
This project focuses on **forecasting India’s headline inflation** using a combination of **statistical** and **machine learning–based hybrid time series models**. Accurate inflation forecasting plays a vital role in shaping monetary policy and ensuring economic stability, especially for institutions like the **Reserve Bank of India (RBI)**.

The study integrates classical econometric models such as **ARIMA** and **Prophet** with modern **deep learning models** like **LSTM**, leveraging their complementary strengths to improve both accuracy and interpretability.

---

## 🎯 Objectives
- Model and forecast India’s **headline inflation rate** using hybrid time series frameworks.  
- Compare the performance of **statistical**, **machine learning**, and **hybrid** models.  
- Evaluate accuracy using metrics like **RMSE**, **MAE**, and **MAPE**.  
- Visualize inflation patterns and generate short- and medium-term forecasts.

---

## 🧩 Methodology

### 1. Data Collection
- **Source:** Reserve Bank of India (RBI) and Ministry of Statistics and Programme Implementation (MOSPI).  
- **Frequency:** Monthly time series data.  
- **Coverage:** Several years of historical headline inflation data (up to 2025).

### 2. Data Preprocessing
- Handling missing values and outliers.  
- Log transformation and differencing for stationarity.  
- Train–test split for out-of-sample performance evaluation.

### 3. Model Development
- **Statistical Models:** ARIMA, SARIMA  
- **Machine Learning Models:** LSTM, Prophet  
- **Hybrid Models:**  
  - **ARIMA–LSTM:** Combines ARIMA’s linear modeling capability with LSTM’s nonlinear pattern recognition.  
  - **ARIMA–Prophet:** Utilizes Prophet’s seasonality detection with ARIMA residual learning.

### 4. Evaluation Metrics
- Root Mean Square Error (RMSE)  
- Mean Absolute Percentage Error (MAPE)  
- R² Score  

### 5. Visualization
- Trend and seasonality decomposition plots  
- Actual vs. predicted inflation plots  
- Forecast intervals for upcoming months

---

## 📊 Results and Insights
- Hybrid models, particularly **ARIMA–LSTM**, achieved superior forecasting accuracy compared to standalone models.  
- The hybrid frameworks effectively captured both **linear trends** and **nonlinear shocks** in inflation.  
- The results demonstrate that integrating machine learning with econometric models can enhance predictive performance for macroeconomic indicators.

---

## 🛠️ Tools and Libraries
- **Language:** Python  
- **Key Libraries:**  
  - Data Handling: `pandas`, `numpy`  
  - Time Series Modeling: `statsmodels`, `pmdarima`, `prophet`  
  - Deep Learning: `tensorflow`, `keras`  
  - Evaluation and Visualization: `scikit-learn`, `matplotlib`, `seaborn`, `plotly`

---

## 📁 Project Files
- `Forecasting_Headline_Inflation_with_Hybrid_Time_Series_Models.ipynb` – main Jupyter Notebook  
- `data/` – contains the inflation dataset  
- `outputs/` – includes forecast plots and model results  
- `README.Rmd` or `README.md` – project documentation  
- `requirements.txt` – Python dependencies

---

## 🔍 Future Work
- Explore ensemble and boosting models such as **XGBoost** and **CatBoost**.  
- Extend to **multivariate forecasting** by incorporating macroeconomic indicators (e.g., repo rate, crude oil price, CPI components).  
- Implement **nowcasting** frameworks for real-time inflation tracking.  

---

## 👩‍💻 Author
**Chandrima Hazra**  
Independent Researcher | MSc in Statistics  
Bangalore, India  
📧 chandrima.hazra2003@gmail.com  
🔗 https://www.linkedin.com/in/chandrima-hazra/

---

## 🏦 Acknowledgments
- **Reserve Bank of India (RBI)** – for providing public inflation data.  
- **MOSPI** – for supporting datasets and statistical resources.  
- **Open-source Python community** – for enabling transparent and reproducible research.

---

## 📄 License
This project is open-sourced under the **MIT License**. You are free to use, modify, and share it with proper attribution.
