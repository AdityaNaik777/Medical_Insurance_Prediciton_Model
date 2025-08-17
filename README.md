# 🏥 Medical Insurance Prediction

This project predicts **medical insurance charges** based on factors such as age, sex, BMI, number of children, smoking habits, and region. It applies **machine learning regression models** to estimate charges and evaluates them using error metrics.

---

## 📌 Project Overview
The goal of this project is to:
- Load and analyze the **Medical Insurance dataset**.
- Preprocess the data (encode categorical variables, scale features).
- Train and evaluate **regression models**.
- Compare results using **Root Mean Squared Error (RMSE)**.

---

## ⚙️ Steps Implemented

### 1. Data Preprocessing
- Loaded dataset using **pandas**.
- Checked dataset info and statistics.
- Converted categorical variables (`sex`, `smoker`, `region`) into numerical values.
- Defined features (X) and target (`charges`).

### 2. Model Training
- Implemented and trained:
  - **Linear Regression**
  - **SGD Regressor**
- Scaled features before applying models.

### 3. Model Evaluation
- Used **Root Mean Squared Error (RMSE)** as the main metric.
- Compared RMSE values for both models.

---

## 📊 Results
- **SGD Regressor outperformed Linear Regression** with a lower RMSE.  
- This indicates that **SGD was a better fit** for this dataset in the current setup.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/AdityaNaik777/Medical_Insurance_Prediciton_Model.git

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Medical_Insurance_Project.ipynb

## 📌 Future Improvements
- Add **train-test split** for more realistic evaluation.
- Try advanced models such as **Random Forest, Gradient Boosting, or XGBoost**.
- Can try with other evaluation metrics and reason why to use a specific metric
- Deploy the model with a **Flask/Django web interface**.
