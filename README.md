# 🌬️ TSA Wind Energy Forecasting

Forecasting wind power output using Time Series Analysis (TSA) and Machine Learning models on the Global Energy Forecasting Competition 2012 dataset.

---

## 📌 Project Overview

This project addresses wind energy forecasting using a combination of statistical modeling and modern ML techniques. The dataset originates from **GEFC 2012**, containing meteorological and wind turbine data.

We explore preprocessing, feature engineering, and forecasting using:

- 📊 **ARIMA (AutoRegressive Integrated Moving Average)**
- 🤖 **CatBoost Regressor**
- ⚡ **LightGBM Regressor**

---

## 🧰 Technologies & Libraries Used

- Python 3.x
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- CatBoost, LightGBM
- Statsmodels (ARIMA)
- Jupyter Notebook

---

## 📈 Model Performance

| Model              | RMSE Score |
|-------------------|------------|
| CatBoost Regressor| **0.17108** |
| LightGBM          | 0.18090    |

---

## 🗂️ Project Structure


tsa-wind-energy-forecasting/
├── tsa-wind-power-forecasting.ipynb # Jupyter Notebook
├── FINAL_submission.csv # Final predictions
├── saveing_processed_tests.csv # Preprocessed data
├── Submission_wind_forecast.csv # Submission file
└── README.md # Project documentation


---

## 🧪 Key Steps

- ✅ Data Cleaning & Handling Missing Values
- ✅ Feature Engineering
- ✅ Model Training & Tuning (GridSearchCV)
- ✅ Evaluation using RMSE
- ✅ Comparison of Statistical & ML models

---

## 📊 Dataset

- 📁 Source: Global Energy Forecasting Competition 2012
- ⏱️ Type: Time Series (hourly data)
- 🌍 Zones: Multiple wind turbine regions with meteorological variables

---

## 🔮 Forecast Output

The forecasting focuses on predicting the wind power generation based on weather inputs and turbine metadata over time.

---

## ✅ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/dipakgawalwad/tsa-wind-energy-forecasting.git
   cd tsa-wind-energy-forecasting

jupyter notebook tsa-wind-power-forecasting.ipynb



---

### ✅ How to Use It:
1. Open your local `README.md` file with Notepad or VS Code.
2. **Delete the current content.**
3. **Paste the new version** above and save.
4. Run in Git Bash:

```bash
git add README.md
git commit -m "Updated professional README"
git push

