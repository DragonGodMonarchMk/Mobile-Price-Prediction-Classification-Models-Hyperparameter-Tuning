# Mobile-Price-Prediction-Classification-Models-Hyperparameter-Tuning
This project builds machine learning models to classify mobile phones into different price ranges based on their specifications. It includes data preprocessing, feature engineering, Exploratory Data Analysis (EDA), and the application of classification algorithms with hyperparameter tuning for better accuracy.
# 📱 Mobile Price Prediction: Classification Models & Hyperparameter Tuning

## 📊 Project Overview
This project aims to **predict the price range of mobile phones** based on their hardware and software specifications. By applying **classification machine learning models**, we explore patterns in mobile features and build models capable of categorizing phones into different price segments.

The workflow includes:
- Data preprocessing & cleaning
- Exploratory Data Analysis (EDA) with visualization
- Training multiple classification models
- Hyperparameter tuning for performance optimization
- Model evaluation & comparison

---

## 📂 Dataset
Datasets used:
- **train.csv** – Training dataset with labeled mobile price ranges  
- **test.csv** – Test dataset without price labels (for prediction)

Features include:
- Battery power, RAM, Internal Memory, Screen dimensions
- Camera specifications
- Connectivity features (Bluetooth, 4G, Wi-Fi, etc.)
- Other phone attributes

Target variable: **Price Range** (0 = Low Cost, 1 = Medium Cost, 2 = High Cost, 3 = Very High Cost)

---

## ⚙️ Technologies Used
- **Python**
- **Pandas, NumPy** (Data handling)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Classification & hyperparameter tuning)
- **XGBoost** (Advanced model)
- **Jupyter Notebook**

---

## 🧠 Machine Learning Models
The following classification algorithms were tested:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

**Hyperparameter tuning** was performed using GridSearchCV and RandomizedSearchCV.

---

## 📈 Key Insights
- **RAM** and **Battery Power** were found to be the most important features affecting price prediction.
- Models like **Random Forest** and **XGBoost** achieved the highest accuracy after tuning.
- Visualization revealed clear separations between classes for certain features.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mobile-price-prediction.git
pip install -r requirements.txt
jupyter notebook mobile-price-prediction-classification-models.ipynb
