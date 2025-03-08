# Demand Forecasting

![Demand Forecasting](Demand_picture.webp)

# 📊 Demand Forecasting Project  

## 1️⃣ Project Overview  
This project applies **time series forecasting** using **LightGBM** to predict sales for **50 products across 10 stores** over a three-month period. The dataset spans **five years (2013-01-01 to 2017-12-31)**.  

### 🔹 Key Techniques Used:
- **Time series decomposition** (trend, seasonality, cyclical, residual components).  
- **Feature engineering** (date-based features, lag features, rolling windows, exponentially weighted features).  
- **Chronological train-test split** and **rolling/expanding window cross-validation**.  

### 📈 Business Insights & Forecast Results:
- **Predicted total sales for the next three months**: **2,558,788.02 items**.  
- **Top-performing stores:** 🏆 Stores **2, 3, and 8**.  
- **Lower-performing stores:** ❌ Stores **5, 6, and 7**.  
- **Best-selling products:** ⭐ **Items 15 and 28**.  
- **Least-sold product:** ⚠️ **Item 5**.  

The forecasts align with historical sales patterns, demonstrating the importance of **seasonality, trends, and residual components** in sales predictions.  

This project follows a **real-world data science workflow**, adhering to the **CRISP-DM framework** and integrating best practices such as **exception handling, modular coding, version control, and virtual environments**, ensuring **reproducibility**.  

---

## 2️⃣ Technologies & Tools  
This project leverages the following technologies:  
- **Programming & Libraries:**  
  - Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Statsmodels, Optuna)  
- **Development & Version Control:**  
  - Jupyter Notebook, Git, and GitHub  
- **Machine Learning & Statistical Methods:**  
  - Regression models, time series analysis  
- **Project Environment:**  
  - Anaconda (virtual environments) and Visual Studio Code  

---

## 3️⃣ Project Structure  
The repository is structured as follows:  

