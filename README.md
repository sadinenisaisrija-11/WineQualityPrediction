# WineQualityPrediction
# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the quality of red wine using Machine Learning classification algorithms. The prediction is based on physicochemical properties such as acidity, alcohol content, pH, sulphates, density, and other chemical characteristics.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, performance evaluation, and comparison of multiple classification algorithms.

---

## 🎯 Objective

To build and compare multiple machine learning classification models that accurately predict whether a wine is of good or bad quality based on its chemical properties.

---

## 📂 Dataset

- **Dataset Name:** Wine Quality Dataset
- **Source:** UCI Machine Learning Repository / Kaggle
- **Total Records:** 1,599
- **Features:** 11 Input Features + 1 Target Variable

### Input Features

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target Variable

- Quality

The quality scores were converted into binary classes:

- **Good Quality (1):** Quality ≥ 7
- **Bad Quality (0):** Quality < 7

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset inspection
- Missing value analysis
- Descriptive statistics
- Quality score distribution
- Distribution plots of all features
- Correlation heatmap
- Class imbalance analysis

---

## ⚙ Data Preprocessing

- Checked missing values
- Feature Engineering
- Converted quality into binary classification
- Train-Test Split (80:20)
- Stratified sampling
- Feature Scaling using StandardScaler

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

1. Random Forest Classifier
2. Stochastic Gradient Descent (SGD) Classifier
3. Support Vector Classifier (SVC)

---

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

Random Forest feature importance was also visualized.

---

## 🏆 Best Performing Model

| Model | Accuracy |
|--------|----------|
| Random Forest | **93.75%** |

Random Forest achieved the highest accuracy and was selected as the best model for predicting wine quality.

---

## 📷 Visualizations

The project includes the following visualizations:

### Wine Quality Distribution
<img width="837" height="611" alt="image" src="https://github.com/user-attachments/assets/5da16e4b-0e69-4cf7-9013-bc9d3245bfb1" />

### Distribution Plots
<img width="1385" height="687" alt="image" src="https://github.com/user-attachments/assets/253053ac-d2e9-4aac-bf67-e4d7e395bd56" />

### Correlation Heatmap
<img width="1293" height="678" alt="image" src="https://github.com/user-attachments/assets/451f86ef-8893-4327-9548-ba332e4c176c" />

### Random Forest Confusion Matrix
<img width="682" height="553" alt="image" src="https://github.com/user-attachments/assets/39253544-e813-4648-ade5-a2b20eab031f" />

### SGD Confusion Matrix
<img width="711" height="576" alt="image" src="https://github.com/user-attachments/assets/341a8cf1-5764-471d-859e-910357851646" />

### SVC Confusion Matrix
<img width="702" height="561" alt="image" src="https://github.com/user-attachments/assets/f669e297-41e3-4cbd-8fb9-bb834b21e02b" />

### Feature Importance Plot
<img width="1267" height="680" alt="image" src="https://github.com/user-attachments/assets/6fe7f171-136d-4ce5-a6be-2403059e2c0e" />

### Model Comparison Table
<img width="647" height="135" alt="image" src="https://github.com/user-attachments/assets/542fbe16-9493-4b14-9711-f4ef3ddb46fd" />

## 📁 Project Structure

```
Wine_Quality_Prediction/
│
├── Wine_Quality_Prediction.ipynb
├── winequality-red.csv
├── README.md
├── requirements.txt
│
└── images/
    ├── quality_distribution.png
    ├── feature_distribution.png
    ├── correlation_heatmap.png
    ├── random_forest_cm.png
    ├── sgd_cm.png
    ├── svc_cm.png
    ├── feature_importance.png
    └── model_comparison.png
```

---

## 🚀 Results

- Successfully trained three classification models.
- Random Forest produced the highest prediction accuracy.
- Alcohol, sulphates, and volatile acidity were among the most influential features.
- The trained model can effectively classify wines into good or bad quality categories.

---

## 📚 Future Enhancements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- XGBoost and LightGBM implementation
- Multi-class quality prediction
- Deployment using Flask or Streamlit

# Conclusion

In this project, a Wine Quality Prediction model was developed using three machine learning classification algorithms: Random Forest, Stochastic Gradient Descent (SGD), and Support Vector Classifier (SVC). The dataset was preprocessed by handling class imbalance through binary classification, performing feature scaling, and splitting the data into training and testing sets using stratified sampling.

After evaluating all three models using accuracy, classification reports, and confusion matrices, the Random Forest Classifier achieved the highest accuracy of **93.75%**, making it the best-performing model. Feature importance analysis also showed that attributes such as alcohol, sulphates, and volatile acidity had a significant influence on wine quality prediction.

Overall, the project demonstrates that machine learning techniques can effectively classify wine quality based on physicochemical properties. Among the evaluated models, the Random Forest Classifier is the most suitable for deployment due to its high accuracy, robustness, and ability to provide interpretable feature importance.

