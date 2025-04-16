# Pytorch-Rice_Classification
# 🌾 Rice Type Classification using PyTorch

This project is a classification task that predicts the type of rice grain using various physical features of the grain. The dataset contains multiple classes of rice types and is processed and modeled using PyTorch. This notebook is inspired by `Ex_1_Tabular_Classification.ipynb`.

---

## 📦 Technologies Used

- Python 🐍
- PyTorch 🔥
- Pandas
- Scikit-learn
- Matplotlib
- OpenDatasets (for downloading the dataset)

---

## 🧪 Steps Performed

1. **Library Installation**  
   Install any required libraries such as `opendatasets` to fetch the dataset from Kaggle.

2. **Library Imports**  
   Import necessary libraries for data loading, preprocessing, model training, and visualization.

3. **Data Loading**  
   Load the rice classification dataset using `opendatasets` and read it with `pandas`.

4. **Data Cleaning**  
   Drop missing values and check for dataset consistency.

5. **Exploratory Data Analysis (EDA)**  
   - Preview the dataset
   - Understand class distribution
   - Prepare feature and target columns

6. **Normalization**  
   Standardize numerical features for better model convergence.

7. **Train-Test Split**  
   Divide the dataset into training and testing sets using `train_test_split`.

8. **Model Training (PyTorch)**  
   - Build a simple feedforward neural network
   - Train the model using cross-entropy loss and an optimizer

9. **Model Evaluation**  
   Evaluate the model’s performance on unseen data using accuracy.

---
