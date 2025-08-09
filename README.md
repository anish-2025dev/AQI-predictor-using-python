## **Short Project Description**

This project predicts the Air Quality Index (AQI) for different cities in India using historical air pollution data downloaded from the [Central Pollution Control Board of India](https://airquality.cpcb.gov.in/AQI_India/). It includes end-to-end steps starting from data loading, cleaning, exploratory analysis, feature engineering, and training multiple machine learning models. The best-performing model is selected after hyperparameter tuning and used for AQI predictions on custom city-date inputs.

---

## **README.md** (with dataset source)

````markdown
# 🌏 Air Pollution Prediction using Machine Learning

## 📌 Project Overview
This project predicts the **Air Quality Index (AQI)** for various cities using historical air pollution data.  
The workflow covers:
- **Data Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Model Training & Comparison**
- **Hyperparameter Tuning**
- **Final Prediction Function**

The final model helps estimate AQI based on city and date inputs, which can be useful for environmental monitoring and public awareness.

---

## 📂 Dataset
- **Source:** All historical air quality data was downloaded from the  
  [Central Pollution Control Board of India](https://airquality.cpcb.gov.in/AQI_India/).
- **Features:**
  - `Date` — Observation date
  - `City` — City name
  - `AQI` — Air Quality Index
  - Other pollutant concentration measures (PM2.5, PM10, etc.)

---

## 📊 Exploratory Data Analysis
The EDA includes:
- AQI distribution plots
- Trends over time
- City-wise pollution comparisons
- Correlation heatmaps

---

## 🧠 Model Building
We experimented with:
- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting**
- **XGBoost**

We selected the best-performing model based on **MAE** and **R² score**.

---

## 🔧 Hyperparameter Tuning
Used `GridSearchCV` / `RandomizedSearchCV` to optimize model performance.

---

## 🚀 Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Air-Pollution-Prediction.git
cd Air-Pollution-Prediction
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

Open `Air_pollution.ipynb` in Jupyter Notebook or Google Colab.

### 4️⃣ Predict AQI

Inside the notebook, use:

```python
predict_aqi("Delhi", "2024-08-10")
```

---

## 📈 Results

* The best model achieved **R² > 0.9** and low **MAE**.
* AQI predictions closely matched historical trends.

---
