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
- **Source:** Historical air pollution data (CSV file)
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

## 📜 License

This project is licensed under the MIT License.

```

