# 📱 Mobile Price Prediction

This project involves analyzing and modeling mobile phone pricing data to build a robust machine learning model capable of predicting mobile price ranges based on hardware specifications. The entire pipeline includes preprocessing, handling outliers, testing multiple algorithms, and evaluating model performance.

---

## 🔍 Project Overview

The goal is to determine the price range (e.g., low, medium, high, premium) of mobile phones using features such as RAM, battery power, camera megapixels, and more.

---

## 📊 Dataset

The dataset includes various features of mobile phones such as:

- Battery power
- RAM
- Internal memory
- Clock speed
- Number of cores
- Primary & front camera resolution
- 4G/3G/WiFi support
- Price range (target variable)

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas & NumPy (Data Handling)
- Scikit-learn (ML Models, Preprocessing, Evaluation)
- Matplotlib & Seaborn (Visualization)
- Joblib (Model Saving)

---

## 🧼 Data Preprocessing

The dataset underwent several cleaning and transformation steps:

- Conversion of data types
- Null value analysis
- Outlier detection and handling using IQR method
- Normalization and scaling

---

## 🧪 Model Testing

Several machine learning models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting

Each model was evaluated based on accuracy, precision, recall, and F1 score.

---

## ✅ Best Performing Model

Random Forest and Gradient Boosting performed well on this dataset. Model selection was finalized using cross-validation and accuracy comparisons.

---

## 📁 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/mobile-price-prediction.git
   cd mobile-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook MobilePrice.ipynb
   ```

---

## 🧠 Future Improvements

- Hyperparameter tuning using GridSearchCV or Optuna
- Deployment via Flask or Streamlit
- Ensemble learning with stacked models
- Feature selection automation

---

## 📌 Conclusion

This project demonstrates a full ML pipeline on a structured dataset, showing how model accuracy can be boosted by proper preprocessing and evaluation. It's a great starting point for applying ML to real-world classification problems.
