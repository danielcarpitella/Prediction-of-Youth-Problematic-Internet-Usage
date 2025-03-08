# Prediction-of-Youth-Problematic-Internet-Usage

This repository contains the work carried out to tackle the **Child Mind Institute: Problematic Internet Use** challenge on Kaggle( https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use/overview) . The goal of the project is to compare and analyze different supervised learning models to predict problematic internet use among young individuals.



---

## Project structure

###  1. Exploratory Data Analysis (EDA)  
- Analysis of the distribution of the target variable **sii**.  
- Visualization of class frequency distributions.  

###  2. Preprocessing  
- Consideration of only the common columns between the training and test sets.  
- Handling of missing values.  
- Normalization and encoding of variables, if necessary.  

###  3. Machine Learning Models  
Several classification algorithms were tested, including:  
- **Decision Tree**  
- **Random Forest**  
- **XGBoost**  

To improve performance, the following techniques were applied:  
- **Handling class imbalance**: Use of **SMOTE** and **ADASYN** to balance class distributions.  
- **Feature selection**: Implementation of **RFECV** to reduce data dimensionality.  
- **Hyperparameter optimization**: Use of **GridSearchCV** and **RandomizedSearchCV**.  

###  4. Model Evaluation  
The models were evaluated using:  
- **Accuracy**  
- **Precision, Recall, F1-score**  
- **Confusion Matrix**  
- **Comparison of model performances**
