# 🏠 Predicting Electricity Charges for Vacation Rentals

## 📌 Project Overview

This project aims to build a machine learning model to **predict the daily electricity charges** of a household based on various factors like household size, average temperature, and the availability of an air conditioner.

The project was developed for **LivAnyWhere (LAW) Pvt Ltd.**, a vacation rental company that provides affordable housing across the United States. The goal is to create an **automated, explainable prediction system** that helps LAW suggest personalized rental plans and offer discounts based on expected electricity usage.

---

## 📁 Dataset

The dataset includes historical electricity usage and household information for **over 12,800 households** in vacation regions of the U.S.

**Features include:**

* Household Size
* Average Daily Temperature
* Availability of Air Conditioner (Yes/No)
* Actual Daily Electricity Consumption (in kWh)
* Corresponding Electricity Cost

---

## ⚙️ Tools & Technologies Used

* **Python**
* **Pandas** – for data handling and preprocessing
* **Matplotlib / Seaborn** – for data visualization
* **Scikit-learn** – for regression modeling and evaluation
* **Jupyter Notebook** – for interactive development

---

## 🧠 Machine Learning Approach

* **Model**: Multivariable Linear Regression
* **Target Variable**: Daily electricity cost (in USD)
* **Features Used**: Household size, average temperature, AC availability
* **Data Preprocessing**:

  * Handling categorical variables (e.g., one-hot encoding for AC availability)
  * Feature scaling
  * Splitting into training and testing sets

---

## 📊 Results

The trained model demonstrated a strong correlation between input features and daily electricity cost, making reliable predictions for unseen data. It meets the requirement of **explainability**, ensuring transparency in how each prediction is made.

---

## 📈 Future Improvements

* Include additional features such as:

  * Appliance usage
  * Insulation quality
  * Region-specific energy rates
* Extend the model to predict **total electricity cost** based on the customer's duration of stay.
* Try advanced regression techniques (e.g., Ridge, Lasso, Random Forest Regressor) for improved accuracy.

---

## ✅ Conclusion

This project provides LivAnyWhere (LAW) Pvt Ltd. with a **data-driven tool** to estimate electricity charges accurately. It helps offer **personalized, budget-friendly rental plans** and ensures compliance with regulatory standards for explainable AI.

---

## 📂 Files Included

* `PredictElecCost.ipynb` – Jupyter Notebook with complete data analysis and model training
* `README.md` – Project documentation

---

## 🔗 License

This project is for educational and demonstration purposes only.



