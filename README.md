# ✈️ Passenger Satisfaction EDA

This project explores the **Airline Passenger Satisfaction** dataset from Kaggle using various exploratory data analysis (EDA) techniques. The goal is to better understand the factors influencing passenger satisfaction, clean the dataset for modeling, and uncover hidden patterns through visualization and statistical insights.

## 📌 Objectives

- Understand data structure and variable distributions
- Handle missing values and outliers
- Explore relationships between features and satisfaction level
- Improve data quality for further modeling

## 🛠️ What I Did

### 📊 Descriptive Statistics
- Calculated **mean**, **median**, **min**, **max**, and **standard deviation** for numerical variables
- Explored the distribution of categorical variables using value counts

### 🧹 Missing Value Handling
- Identified columns with missing data and calculated their **percentage**
- Imputed missing values using a **model-based approach (Random Forest Imputer)**

### ⚠️ Outlier Detection
- Detected outliers using the **IQR (Interquartile Range)** method
- Visualized and optionally removed extreme values to avoid bias in analysis

### 📈 Data Visualization
- Used **boxplots**, **histograms**, **count plots**, and **violin plots** to explore numerical and categorical data
- Compared satisfaction levels across key features like service quality, flight class, and delay time

## 📁 Dataset

- Source: [Kaggle – Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
- Contains features such as `Gender`, `Flight Distance`, `Inflight service`, `Seat comfort`, `Class`, and `Satisfaction`

## 📎 Tools & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib for visualization
- Scikit-learn (RandomForestImputer)

## 📌 Insights

- Business class passengers reported significantly higher satisfaction
- Flight distance and inflight service quality strongly influence satisfaction
- A few features had minor missing values, which were successfully imputed
- Outliers were mostly found in flight delays and service-related ratings


---

