# App vs Website — Revenue Prediction (Linear Regression)

This project helps an NYC-based fashion e-commerce company decide whether to invest more in their **mobile app** or **website** by analyzing which user activity better predicts **Yearly Amount Spent**.

---

## 🔍 Problem Statement

Customers take in-store styling sessions, then purchase later via **mobile app** or **website**.  
The company wants to know:  
**Which platform drives revenue more — App or Website? Or is Membership duration more important?**

---

## 📂 Dataset Description

Columns used:
- **Avg. Session Length** — average session duration of styling sessions
- **Time on App** — average daily minutes on mobile app
- **Time on Website** — average daily minutes on website
- **Length of Membership** — customer membership duration (years)
- **Yearly Amount Spent** — target variable (USD)

---

## 📊 Methodology

1. **Exploratory Data Analysis**
   - `.head()`, `.describe()`, `.info()`
   - `jointplot`, `pairplot`, `lmplot`

2. **Feature Selection & Train/Test Split**
3. **Linear Regression Model Training**
4. **Prediction & Model Evaluation**
   - MAE, MSE, RMSE
5. **Residual Analysis**
6. **Interpret Coefficients to answer the business question**

---

## 📌 Key Libraries

```python
pandas, numpy, seaborn, matplotlib, sklearn
