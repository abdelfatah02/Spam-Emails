# Spam Classifier Project

## Project Overview

This project uses various machine learning algorithms to classify spam and ham messages. The dataset used for this project is the **SMS Spam Collection Dataset** (https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset). The project demonstrates the usage of **stacking classifiers**, **boosting classifiers**, and **bagging classifiers** to perform binary classification on text data.

### Key Features:
- **Preprocessing**: The dataset is cleaned by removing irrelevant columns, handling missing values, and encoding labels.
- **Text Representation**: TF-IDF (Term Frequency-Inverse Document Frequency) is used to vectorize text data.
- **Modeling**: The project explores three different ensemble models:
  1. **Stacking Classifier** (using Decision Tree, KNN, SVM as base models)
  2. **XGBoost Classifier** (Boosting)
  3. **Bagging Classifier** (using Decision Tree as base model)
  
- **Evaluation**: The models are evaluated using **accuracy**, **precision**, **recall**, **F1-score**, **confusion matrices**, and **ROC curves**.

## Requirements

To run the project, you need to install the following Python packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `xgboost`

You can install these packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
