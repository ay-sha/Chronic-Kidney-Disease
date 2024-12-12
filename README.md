# Chronic Kidney Disease (CKD) Prediction  

## Overview  
This project focuses on predicting Chronic Kidney Disease (CKD) using machine learning techniques. The dataset is preprocessed to handle missing values and clean inconsistencies, followed by implementing classification models to achieve high accuracy in predictions.  

## Features  
- **Data Cleaning**: Handled missing values and corrected inconsistent entries in categorical and numerical columns.  
- **Visualization**: Insights into data distribution using pie charts and bar plots.  
- **Machine Learning Models**: Implemented Logistic Regression and Decision Tree Classifier for classification tasks.  
- **Performance Metrics**: Evaluated models using accuracy, precision, recall, and F1-score.  

## Dataset  
The dataset contains records of patients with information such as age, blood pressure, sugar levels, and other clinical attributes. The target variable is `classification`, indicating whether a patient has CKD (1) or not (0).  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**:  
  - Data Manipulation: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: Scikit-learn  

## Steps Performed  
1. **Data Preprocessing**:  
   - Replaced inconsistent entries in categorical and numerical columns.  
   - Imputed missing values using the most frequent strategy.  
   - Encoded categorical variables using Label Encoding.  
2. **Data Visualization**:  
   - Pie chart to visualize the distribution of CKD and non-CKD cases.  
   - Bar plot to compare model accuracies.  
3. **Model Training**:  
   - Logistic Regression and Decision Tree Classifier were trained on an 80-20 train-test split.  
4. **Evaluation**:  
   - Logistic Regression achieved an accuracy of **91.25%** on the test data.  
   - Decision Tree Classifier achieved an accuracy of **97.5%** on the test data.  
   - Precision, recall, and F1-score were used to compare model performance.  

## Results  
- **Logistic Regression**:  
  - Test Accuracy: **91.25%**  
  - Weighted F1-score: **0.91**  
- **Decision Tree Classifier**:  
  - Test Accuracy: **97.5%**  
  - Weighted F1-score: **0.98**  

## Visualization  
Comparison of model accuracies:  

## Accuracy Comparison
![Capture](https://github.com/user-attachments/assets/d65bd158-6225-4402-8695-c0f0c8e9781d)

## How to Use  
1. Clone this repository.  
2. Load the dataset `kidney_disease.csv`.  
3. Install the required libraries:  
   ```bash  
   pip install pandas numpy matplotlib seaborn scikit-learn  
   ```  
4. Run the notebook or Python script to preprocess the data, train models, and evaluate performance.  
