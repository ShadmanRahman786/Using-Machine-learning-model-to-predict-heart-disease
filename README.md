# Using Machine Learning to Predict Heart Disease

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Machine Learning](https://img.shields.io/badge/ML-Heart%20Disease-red)

---

## 💓 Heart-Pumping Simulation

Watch the heart “beat” while exploring the project:

![Beating Heart](https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif)

---

## Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection is critical. This project leverages machine learning techniques to **predict the likelihood of heart disease** based on patient health data.  

---

## Features

- Data Preprocessing: Handles missing values, scaling, and encoding  
- EDA: Visualizations for feature distributions & correlations  
- ML Models: Logistic Regression, SVM, KNN, Decision Tree, Random Forest  
- Performance Evaluation: Accuracy, precision, recall, F1-score, confusion matrix  
- Bar Charts: Feature differentiation and model performance  

---

##Results

import matplotlib.pyplot as plt

# Model names and accuracies
models = ['Logistic Regression', 'SVM', 'KNN', 'Decision Tree']
accuracy = [86.34, 83.9, 72.2, 100.0]

# Plotting bar chart
plt.figure(figsize=(8,5))
plt.bar(models, accuracy, color=['skyblue', 'orange', 'green', 'red'])
plt.title('Model Accuracy Comparison')
plt.xlabel('Models')
plt.ylabel('Accuracy (%)')
plt.ylim(0, 110)
for i, v in enumerate(accuracy):
    plt.text(i, v + 2, str(v), ha='center', fontweight='bold')
plt.show()

## Installation & Usage


```bash
git clone https://github.com/ShadmanRahman786/Using-Machine-learning-model-to-predict-heart-disease.git
cd Using-Machine-learning-model-to-predict-heart-disease
pip install pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook Heart_Disease_Prediction_Model.ipynb
```

##Author

Shadman Rahman Sameen
	•	Email: shadman.rahman.sameen@g.bracu.ac.bd
	•	GitHub: ShadmanRahman786
	•	Location: Dhaka, Bangladesh
	•	Passionate about Machine Learning, Data Science, and AI
