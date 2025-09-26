# Breast Cancer Classification using Logistic Regression

## Overview
This project implements **binary classification** of breast cancer (malignant vs benign) using **Logistic Regression**. It demonstrates key machine learning steps including data preprocessing, feature scaling, model training, evaluation, and visualization.

## Dataset
- Source: [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Features include measurements of cell nuclei from breast mass images.
- Target variable: `diagnosis` (`M` = malignant, `B` = benign)

## Steps Performed
1. **Data Preprocessing**  
   - Dropped unnecessary columns (`id`, `Unnamed: 32`)  
   - Encoded target variable (`M` → 1, `B` → 0)  

2. **Train/Test Split & Scaling**  
   - Split dataset (80% train, 20% test)  
   - Standardized features using `StandardScaler`

3. **Model Training**  
   - Fitted `LogisticRegression` on training data  

4. **Evaluation Metrics**  
   - Confusion Matrix  
   - Precision & Recall  
   - ROC-AUC Curve  
   - Classification Report  

5. **Threshold Tuning**  
   - Demonstrated effect of changing decision threshold  

6. **Sigmoid Function Visualization**  
   - Explained how logistic regression outputs probabilities  

## Results
- High precision and recall on test data  
- ROC-AUC > 0.95, indicating strong model performance  
- Threshold tuning can balance sensitivity vs specificity  

## Libraries Used
- Python 3.x  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

## How to Run
1. Upload `data.csv` manually if using Google Colab.  
2. Run all notebook cells in order.  
3. Visualizations and metrics will be generated automatically.  

## Key Learning
- Logistic Regression for binary classification  
- Sigmoid function maps outputs to probabilities  
- Importance of evaluation metrics beyond accuracy  
- Threshold tuning for imbalanced data scenarios  

