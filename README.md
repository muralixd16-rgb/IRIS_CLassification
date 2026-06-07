# Iris Flower Classification using Machine Learning

## Project Overview

This project focuses on classifying Iris flower species using various Machine Learning algorithms. The Iris dataset is one of the most popular datasets for learning classification techniques and contains measurements of flower petals and sepals.

## Dataset Information

The dataset contains 150 flower samples belonging to three species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

### Features

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Variable

* Species

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset overview
* Missing value analysis
* Histograms
* Boxplots
* Correlation Heatmap

### Key Findings

* No missing values were present in the dataset.
* Petal Length and Petal Width showed strong positive correlation.
* Petal features provided better class separation than sepal features.

---

## Machine Learning Models Implemented

The following classification algorithms were trained and evaluated:

1. K-Nearest Neighbors (KNN)
2. Logistic Regression
3. Decision Tree
4. Support Vector Machine (SVM)
5. Random Forest

---

## Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| KNN                 | 100%     |
| Logistic Regression | 100%     |
| Decision Tree       | 100%     |
| SVM                 | 100%     |
| Random Forest       | 100%     |

---

## Feature Analysis

To understand feature importance, models were trained separately using:

### Petal Features

* Petal Length
* Petal Width

### Sepal Features

* Sepal Length
* Sepal Width

### Observation

Models trained using petal features consistently achieved higher accuracy than models trained using only sepal features. This indicates that petal measurements are more informative for Iris species classification.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Git
* GitHub

---

## Project Structure

```text
iris_classification/
│
├── iris_classification.ipynb
├── Iris.csv
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Conclusion

This project demonstrates a complete machine learning workflow including data preprocessing, exploratory data analysis, model training, evaluation, and feature analysis. The results show that the Iris dataset is highly separable and can be classified with excellent accuracy using multiple machine learning algorithms.
