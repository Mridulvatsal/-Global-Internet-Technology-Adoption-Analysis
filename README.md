# 🌐 Global Internet & Technology Adoption Analysis

## 📊 Overview

This project analyzes global trends in digital technology adoption using data from the World Bank.

We explore how internet usage, mobile connectivity, broadband access, and GDP interact across countries and time.

---

## 🎯 Objectives

* Analyze global internet growth trends
* Identify top digitally advanced countries
* Study relationship between GDP & internet usage
* Understand impact of mobile connectivity
* Build ML model to predict internet adoption

---

## 📥 Data Source

* World Bank Open Data
* Indicators used:

  * Internet Users (%)
  * GDP per capita
  * Mobile subscriptions
  * Broadband subscriptions

---

## 🧹 Data Processing

* Removed unnecessary columns
* Handled missing values (median/mode)
* Converted wide → long format
* Merged datasets
* Outlier detection (IQR & Z-score)
* Feature engineering

---

## 📊 Key Insights

📈 Internet adoption is growing rapidly worldwide
🌍 Digital divide still exists across countries
📱 Mobile connectivity strongly influences internet usage
💰 GDP positively correlates with digital infrastructure

---

## 🤖 Machine Learning Model

### Models Used:

* Linear Regression
* Random Forest Regressor

### Results:

* **R² Score:** 0.93
* **MAE:** ~3.07

### 🔥 Key Finding:

Previous year internet usage dominates prediction (~94% importance)

---

## 📊 Visualizations

* Internet growth trend
* GDP vs Internet usage
* Cellular vs Internet usage

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Seaborn, Matplotlib, Plotly
* Scikit-learn

---

## 🚀 Future Improvements

* Add time-series models (ARIMA/LSTM)
* Deploy dashboard using Streamlit
* Add country-level clustering

---

## 👨‍💻 Author

**Mridul Vatsal**
Data Science Enthusiast 🚀
