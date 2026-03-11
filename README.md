# Breast Cancer Detection Using Support Vector Machine (SVM)

## Overview
This capstone project applies machine learning techniques to classify breast tumors as **benign** or **malignant** using the **Breast Cancer Wisconsin Diagnostic Dataset**. The project demonstrates how **Support Vector Machine (SVM)** models can assist in early breast cancer detection by analyzing diagnostic features extracted from medical images.

## Dataset
The project uses the **Breast Cancer Wisconsin Diagnostic Dataset (WDBC)**.

**Dataset Information:**
- Total Samples: 569
- Benign: 357
- Malignant: 212
- Features: 30 numerical features
- Target Variable: Diagnosis (Benign or Malignant)

The features describe characteristics of the cell nuclei in digitized images of breast masses such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry

## Project Workflow
1. **Data Loading**
   - Import dataset and inspect structure

2. **Exploratory Data Analysis (EDA)**
   - Analyze feature distributions
   - Check class balance
   - Identify correlations and patterns

3. **Data Preprocessing**
   - Feature scaling
   - Train-test split
   - Data preparation

4. **Model Training**
   - Implement Support Vector Machine (SVM)
   - Train model using training data

5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
   - Performance metrics

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Goal
The goal of this project is to demonstrate how machine learning models can support **early breast cancer detection** by accurately classifying tumors based on diagnostic features.
