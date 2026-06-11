# 🍷 Wine Quality Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting wine quality based on its physicochemical properties using Machine Learning techniques. The objective is to analyze various chemical characteristics of wine and build predictive models capable of estimating wine quality accurately.

The project includes comprehensive Exploratory Data Analysis (EDA), feature engineering, visualization, and implementation of multiple classification algorithms.

---

## 🎯 Objectives

- Analyze the relationship between wine quality and chemical properties.
- Perform data cleaning and preprocessing.
- Visualize trends and patterns within the dataset.
- Train multiple machine learning classification models.
- Compare model performance and identify the best-performing algorithm.
- Determine the most influential factors affecting wine quality.

---

## 📊 Dataset Information

The dataset contains various physicochemical attributes of red wine samples.

### Features

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

- Quality (Wine Quality Score)

---

## 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset inspection
- Missing value analysis
- Duplicate record detection
- Statistical summary
- Quality distribution analysis
- Correlation heatmap
- Alcohol vs Quality analysis
- Volatile Acidity vs Quality analysis
- Sulphates vs Quality analysis
- Density vs Quality analysis
- pH vs Quality analysis
- Pairplot visualization

### Key Insights

- Higher alcohol content is generally associated with better-quality wines.
- Volatile acidity shows a negative correlation with wine quality.
- Sulphates positively influence wine quality.
- Most wine samples belong to quality categories 5 and 6.
- The dataset exhibits moderate class imbalance.

---

## 🤖 Machine Learning Models Used

### 1. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

### 2. Stochastic Gradient Descent (SGD) Classifier

A linear classification model optimized using gradient descent.

### 3. Support Vector Classifier (SVC)

A powerful classification algorithm that identifies optimal decision boundaries between classes.

---

## ⚙️ Data Preprocessing

- Feature Selection
- Train-Test Split
- Feature Scaling using StandardScaler

---

## 📋 Model Evaluation Metrics

The following metrics were used:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Analysis

---

## 📊 Results

| Model | Accuracy |
|---------|----------|
| Random Forest | Best Performing Model |
| SGD Classifier | Moderate Performance |
| Support Vector Classifier | Competitive Performance |

> Random Forest achieved the highest overall accuracy and provided valuable feature importance insights.

---

## 🔍 Important Features

According to the Random Forest model, the most influential features were:

- Alcohol
- Volatile Acidity
- Sulphates
- Total Sulfur Dioxide
- Citric Acid

These attributes significantly contribute to determining wine quality.

---

## 📂 Project Structure

```
Wine-Quality-Prediction/
│
├── Dataset/
│   └── WineQT.csv
│
├── Notebooks/
│   ├── EDA_Wine_Quality.ipynb
│   └── Prediction_Wine_Quality.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

- EDA_Wine_Quality.ipynb
- Prediction_Wine_Quality.ipynb

---

## 🎓 Learning Outcomes

Through this project, the following concepts were explored:

- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Scaling
- Classification Algorithms
- Model Evaluation
- Feature Importance Analysis
- Machine Learning Workflow

---

## 📜 Conclusion

This project demonstrates how machine learning can be applied to predict wine quality using chemical properties. Among the evaluated models, the Random Forest Classifier delivered the best performance and provided meaningful insights into the factors influencing wine quality.

The findings can assist wine producers in understanding quality indicators and support data-driven decision-making in wine production.

---

## 👨‍💻 Author

**Kushagra Pandey**

Machine Learning Enthusiast | Python Developer | Data Science Learner

---

### Internship Project

Completed as part of the **Oasis Infobyte Data Science Internship Program**.