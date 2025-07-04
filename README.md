# 🌍 Carbon Emission Prediction using Machine Learning

A data-driven machine learning project aimed at predicting country-level CO₂ emissions based on economic, demographic, and energy-related indicators. This project was developed as part of the AICTE–Edunet–Shell Skills for Future Internship Program.

---

## 📌 Table of Contents

- [🔍 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [📁 Dataset Description](#-dataset-description)
- [🧠 Methodology](#-methodology)
- [🛠️ Tools & Technologies Used](#-tools--technologies-used)
- [📊 Model Evaluation](#-model-evaluation)
- [✅ Results](#-results)
- [📌 Key Takeaways](#-key-takeaways)
- [🚀 Future Improvements](#-future-improvements)
- [📸 Sample Outputs](#-sample-outputs)

---

## 🔍 Project Overview

Carbon dioxide (CO₂) emissions are a primary driver of global warming and climate change. Accurate prediction of emissions based on country-specific factors can help governments, industries, and international bodies take informed actions toward reducing the global carbon footprint.

This project uses machine learning regression techniques to build predictive models for national CO₂ emissions using open-source historical datasets.

---

## 🎯 Objectives

- Predict CO₂ emissions using historical socio-economic and energy data.
- Identify key features influencing emissions at the national level.
- Evaluate and compare the performance of regression models.
- Provide insights for climate action planning using interpretable ML models.

---

## 📁 Dataset Description

The dataset includes:
- GDP per capita
- Energy use (per capita)
- Population size
- Renewable vs. non-renewable energy usage
- Urbanization rate
- Historical CO₂ emissions

**Source**: Aggregated from World Bank, UN Statistics, and global climate databases.

---

## 🧠 Methodology

1. **Data Cleaning**
   - Handling missing values
   - Feature scaling and encoding

2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Trend and distribution analysis

3. **Feature Selection**
   - Recursive Feature Elimination (RFE)

4. **Model Building**
   - Linear Regression (baseline)
   - Random Forest Regressor (optimized)

5. **Evaluation**
   - MAE, RMSE, and R² Score

---

## 🛠️ Tools & Technologies Used

- Python 3.x  
- Pandas, NumPy – Data manipulation  
- Matplotlib, Seaborn – Visualization  
- Scikit-learn – Machine learning models  
- Jupyter Notebook – Development environment

---

## 📊 Model Evaluation

| Model                 | R² Score | MAE     | RMSE    |
|----------------------|----------|---------|---------|
| Linear Regression     | 0.65     | 1.27    | 1.98    |
| Random Forest Regressor | **0.85**  | **0.68** | **1.12** |

✅ Random Forest clearly outperforms the linear model with better generalization and lower error.

---

## ✅ Results

- GDP per capita and energy usage are the most significant predictors of carbon emissions.
- The model can be scaled to make predictions for countries with limited recent data.
- Visualizations reveal strong correlation between economic growth and environmental impact.

---

## 📌 Key Takeaways

- Machine learning can effectively forecast emissions using socio-economic data.
- Interpretability helps in aligning data science with real-world climate policy decisions.
- Data gaps in developing nations pose a challenge—but predictive models can fill those gaps.

---

## 🚀 Future Improvements

- Integrate time-series forecasting (e.g., ARIMA, LSTM)
- Include climate policy and carbon tax data
- Build a dashboard to visualize emissions predictions in real time

---

## 📸 Sample Outputs

> Feature Importance (Random Forest)  
![Feature Importance](assets/feature_importance.png)

> Predicted vs Actual CO₂ Emissions  
![Prediction Plot](assets/predicted_vs_actual.png)

---

## 👤 Author

**Dhanasekar**  
AICTE-Edunet Internship Program 2025  
GitHub: [@dhana-dev6](https://github.com/dhana-dev6)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

