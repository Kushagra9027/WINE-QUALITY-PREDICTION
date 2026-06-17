# 🍷 Wine Quality Prediction Using Machine Learning

## Oasis Infobyte Data Analytics Internship - Level 2 Project

### 📌 Project Overview

This project focuses on predicting wine quality based on its physicochemical properties using Machine Learning techniques. The objective is to analyze various chemical characteristics of wine and develop predictive models capable of accurately classifying wine quality.

The project includes comprehensive Exploratory Data Analysis (EDA), data visualization, feature engineering, model training, and performance evaluation using multiple machine learning algorithms.

---

## 🎯 Objectives

* Analyze the relationship between wine quality and chemical properties.
* Perform data cleaning and preprocessing.
* Visualize trends and patterns within the dataset.
* Train and evaluate multiple classification models.
* Compare model performance using standard evaluation metrics.
* Identify the most influential features affecting wine quality.

---

## 📊 Dataset Information

The dataset contains physicochemical properties of wine samples along with their quality ratings.

### Features

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

### Target Variable

* Quality (Wine Quality Score)

### Dataset Source

The dataset is included in the repository under the `dataset/` folder.

---

## 🛠 Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Development Environment

* Jupyter Notebook
* VS Code

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Inspection
* Missing Value Analysis
* Duplicate Record Detection
* Statistical Summary
* Quality Distribution Analysis
* Correlation Analysis
* Pairplot Visualization
* Feature Relationship Analysis

### Visualizations Generated

* Quality Count Plot
* Correlation Heatmap
* Alcohol vs Quality
* Volatile Acidity vs Quality
* Sulphates vs Quality
* Density vs Quality
* pH vs Quality
* Pairplot Analysis

---

## 🔍 Key Insights

* Higher alcohol content is generally associated with better-quality wines.
* Volatile acidity exhibits a negative relationship with wine quality.
* Sulphates positively contribute to wine quality.
* Most wine samples belong to quality categories 5 and 6.
* Certain chemical properties have stronger predictive power than others.
* The dataset contains moderate class imbalance across quality levels.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Data Cleaning
* Duplicate Removal
* Feature Selection
* Train-Test Split
* Feature Scaling using StandardScaler

---

## 🤖 Machine Learning Models Implemented

### 1. Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees to improve classification performance and feature interpretability.

### 2. Stochastic Gradient Descent (SGD) Classifier

A linear classification model optimized using gradient descent for efficient training.

### 3. Support Vector Classifier (SVC)

A powerful classification algorithm that identifies optimal decision boundaries between classes.

---

## 📋 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix
* Feature Importance Analysis

### Performance Comparison

The performance of all implemented models was compared to identify the most effective approach for wine quality prediction.

### Best Performing Model

🏆 **Random Forest Classifier**

The Random Forest model achieved the best overall performance and provided valuable insights into feature importance.

---

## 📊 Feature Importance Analysis

The Random Forest model was used to determine the most influential features affecting wine quality.

### Top Contributing Features

* Alcohol
* Volatile Acidity
* Sulphates
* Total Sulfur Dioxide
* Citric Acid

These features played a significant role in determining wine quality and contributed heavily to model predictions.

---

## 🖼 Generated Visualizations

The project includes the following visualizations stored in the `images/` directory:

* Correlation Heatmap
* Pairplot
* Quality Count Plot
* Alcohol vs Quality
* Volatile Acidity vs Quality
* Sulphates vs Quality
* Density vs Quality
* pH vs Quality
* Model Comparison Chart
* Random Forest Confusion Matrix
* Top 10 Important Features

---

## 📂 Project Structure

```text
pro_2_Wine_Quality_Prediction/
│
├── dataset/
│   └── WineQT.csv
│
├── images/
│   ├── heatmap.png
│   ├── Model Comparison.png
│   ├── pairplot.png
│   ├── quality_label_vs_alcohol.png
│   ├── quality_vs_alcohol.png
│   ├── quality_count.png
│   ├── quality_vs_density.png
│   ├── quality_vs_ph.png
│   ├── quality_vs_sulphates.png
│   ├── quality_vs_volatile_acidity.png
│   ├── Random Forest Confusion Matrix.png
│   └── Top 10 Important Features.png
│
├── ml_models_prediction/
│   └── Prediction_Wine_Quality.ipynb
│
├── notebooks/
│   └── EDA_Wine_Quality.ipynb
│
└── README.md
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone <repository-url>
```

### Navigate to the Project Directory

```bash
cd pro_2_Wine_Quality_Prediction
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

* `notebooks/EDA_Wine_Quality.ipynb`
* `ml_models_prediction/Prediction_Wine_Quality.ipynb`

---

## 🎓 Learning Outcomes

This project helped develop practical skills in:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Data Preprocessing
* Classification Algorithms
* Model Evaluation
* Feature Importance Analysis
* End-to-End Machine Learning Workflow

---

## 📜 Conclusion

This project demonstrates the practical application of machine learning techniques in predicting wine quality using physicochemical properties.

Through extensive exploratory analysis and model comparison, the Random Forest Classifier emerged as the best-performing model. The study highlights the importance of chemical attributes such as alcohol content, sulphates, and volatile acidity in determining wine quality.

The insights gained from this analysis can assist wine producers in understanding quality indicators and support data-driven decision-making in wine production processes.

---

## Internship Information

**Organization:** Oasis Infobyte
**Domain:** Data Analytics
**Project Level:** Level 2
**Project Title:** Wine Quality Prediction

---

## 👨‍💻 Author

**Kushagra Pandey**

B.Tech Computer Science & Engineering
Jaypee Institute of Information Technology (JIIT), Noida

### Connect With Me

* GitHub: https://github.com/Kushagra9027
* LinkedIn: Add Your LinkedIn Profile Link Here
