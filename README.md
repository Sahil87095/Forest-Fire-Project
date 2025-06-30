# 🔥 Forest Fire Likelihood Prediction

A complete machine learning project to predict the likelihood & intensity of forest fires for a algerian forest fire dataset. The project follows the full ML lifecycle—from data cleaning to deployment.

---

## 📁 Project Overview

- Predicts the likelihood & intensity of a forest fire.
- Uses satellite data: temprature, relative humidity, wind speed, rain, and more.
- Built using Python, Numpy, Pandas, Scikit-learn, Flask, and Jupyter Notebooks.

---

## 📊 Dataset

The dataset includes:
- **Temprature**
- **RH(Relative Humidity)**
- **WS(Wind Speed)**
- **Rain** 
- **FFMC(Fine Fuel Moisture Code)**
- **DMC(Duff Moisture Code)**
- **DC(Drought Code)** 
- **ISI(Initial Speed Index)**
- **BUI(Buildup Index)**
- **FWI(Fire Weather Index)**
- **Classes** 

---

## 🛠 Steps Involved

1. **Data Cleaning**
   - Removed irrelevant columns like `day`, `month`, `year`.
   - Changed the datatypes of required columns.
   - Created seprate regions.
   - No missing values.

2. **Feature Engineering**
   - Converted `classes` to numeric.
   - One-hot encoded `type`.
   - Removed some highly correlated columns.

3. **Model Building**
   - Used linear regression,ridge & lasso regression.
   - Evaluated using metrics like R², MAE, MSE.
   - Used `train_test_split` and cross-validation.

4. **Deployment**
   - Deployed via a Flask API.
