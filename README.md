# Kaggle Classification Competitions Repository

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png" width="50%">
</p>


This repository contains solutions for various Kaggle classification competitions, showcasing approaches to both binary and multiclass classification problems.

---

## Table of Contents

1. [Repository Structure](#repository-structure)
2. [Included Competitions](#included-competitions)
3. [Features](#features)
4. [How to Use](#how-to-use)
5. [Dependencies](#dependencies)

---

## Repository Structure

```plaintext
classification-competitions/
│
├── mushroom_characteristics/          # Mushroom classification competition
│   ├── playground-series-s4e8/        # Data files for the competition
│   │   ├── sample.csv                 # Dataset sample
│   │   ├── sample_submission.csv      # Sample submission file
│   │   ├── test.ipynb                 # Notebook for testing the model
│   ├── classification.ipynb           # Modeling and analysis notebook
│   ├── submission.csv                 # Final predictions
│   └── README.md                      # Mushroom competition README
│
├── spacecraft_classification/         # Spacecraft classification competition
│   ├── train.csv                      # Training data
│   ├── test.csv                       # Testing data
│   ├── submission.csv                 # Final submission file
│   ├── classification.ipynb           # Modeling and analysis notebook
│   ├── mock.ipynb                     # Mock analysis notebook
│   └── README.md                      # Spacecraft competition README
│
└── README.md                          # Main repository README
```

## Included Competitions

1. **Mushroom Classification**
   - **Folder**: `mushroom_characteristics/`
   - **Goal**: Predict mushroom characteristics based on various categorical features.
   - **Dataset**: Provided in the `playground-series-s4e8/` subfolder.

2. **Spacecraft Classification**
   - **Folder**: `spacecraft_classification/`
   - **Goal**: Classify spacecrafts based on feature data (e.g., performance metrics).

---

## Features

### **Exploratory Data Analysis (EDA)**
- Visualizing distributions and relationships.
- Handling missing values and outliers.

### **Feature Engineering**
- Categorical encoding using techniques like one-hot encoding.
- Advanced feature transformations for better predictions.

### **Modeling**
- Tried-and-tested models like Logistic Regression, CatBoost, and LightGBM.
- Hyperparameter tuning and model selection.

### **Evaluation**
- Metrics such as accuracy, F1-score, precision, and recall.
