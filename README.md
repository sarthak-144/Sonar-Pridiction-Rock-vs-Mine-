# Sonar Object Classification Project

## Overview
This project is a Python-based machine learning model designed to classify objects as either a **rock** or a **mine** based on sonar input data. The model uses the **Logistic Regression** algorithm from the `sklearn` library to perform the analysis and prediction.

## Features
- Input sonar signals for object detection.
- Classify objects into two categories: **Rock** or **Mine**.
- Built using Python and Scikit-learn for efficient and reliable performance.

---

## Table of Contents
1. [Usage](#usage)
2. [Project Structure](#project-structure)
3. [Data Description](#data-description)
4. [Model Overview](#model-overview)
5. [Results](#results)

---

## Usage

1. Place your sonar dataset file (`sonar_data.csv`) in the project directory.
2. Run the main Python script:
   ```bash
   python sonar.ipynb
   ```
3. Input a sonar sample to get predictions:
   - The program will preprocess the data and output whether the object is a **rock** or a **mine**.

---

## Project Structure
```
sonar-object-classification/
|├── sonar_classifier.py         # Main script to train and predict
|├── Sonar.ipynb                # Jupyter Notebook version
|└── README.md                # Project documentation
```

---

## Data Description

The dataset used for this project contains:
- **Features**: Numerical values representing sonar signal frequencies.
- **Labels**: Two categories:
  - `R` for Rock
  - `M` for Mine

Each sample consists of 60 features derived from sonar signals.

---

## Model Overview

The model uses **Logistic Regression** for classification. Key steps include:
1. Splitting the dataset into training and testing sets.
2. **Model Training**:
   - Logistic Regression is trained on the training set.
3. **Prediction**:
   - Predictions are made on the testing set and/or new inputs.

---

## Results

The Logistic Regression model achieves the following metrics:
- **Accuracy on training data**: 0.8342245989304813
- **Accuracy on test data**: 0.7619047619047619

---

### Author
- [GitHub Profile](https://github.com/sarthak-144)


