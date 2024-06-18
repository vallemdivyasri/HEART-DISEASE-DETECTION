# HEART-DISEASE-DETECTION
This repository contains a project focused on detecting heart disease using machine learning techniques. The primary goal is to build a predictive model that can help identify individuals at risk of heart disease based on their medical data.

## Project Overview
Heart disease is a leading cause of death globally, making early detection critical. By leveraging data science, we aim to create a reliable model that can assist healthcare professionals in making informed decisions.

## Data
The dataset used in this project is sourced from Kaggle. 
It includes various features such as,
1. Age
2. Sex
3. Chest pain type (4 values)
4. Resting blood pressure
5. Serum cholesterol in mg/dl
6. Fasting blood sugar > 120 mg/dl
7. Resting electrocardiographic results (values 0, 1, 2)
8. Maximum heart rate achieved
9. Exercise-induced angina
10. Oldpeak = ST depression induced by exercise relative to rest
11. The slope of the peak exercise ST segment
12. Number of major vessels (0-3) colored by fluoroscopy
13. Thal: 3 = normal; 6 = fixed defect; 7 = reversible defect

## Model
A Random Forest classifier was chosen for its robustness and ability to handle the imbalanced nature of medical datasets. The model was trained and tested on the dataset, achieving an accuracy of 98%.

### Key Steps:
**Data Preprocessin**: Handling missing values, encoding categorical variables, and normalizing numerical features.

**Feature Selection:** Identifying and selecting the most relevant features.

**Model Training:** Training the Random Forest classifier with optimized hyperparameters.

**Model Evaluation:** Assessing the model's performance using accuracy, precision, recall, and F1-score metrics.

## Results
The Random Forest classifier achieved an impressive accuracy of 98% on the test set, indicating a high level of reliability in predicting heart disease presence.
