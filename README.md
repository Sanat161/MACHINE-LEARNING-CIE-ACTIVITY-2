# 🏠 House Price Prediction using Linear Regression

## 👨‍🎓 Student Information

| Details | Information |
|---|---|
| Name | Sanat Ramteke |
| Roll Number | AD3307 |
| Division | C |
| Branch | B.Tech – Artificial Intelligence and Data Science |
| Subject | Machine Learning |
| Activity | Activity 2 |

---

## 📌 Project Overview

This project focuses on predicting house prices using **Linear Regression**, a supervised machine learning algorithm.

The model uses the distance to the nearest MRT station as an input feature to predict the house price per unit area.

The project is created using Python and the Real Estate Valuation dataset from the UCI Machine Learning Repository.

## 🎯 Project Objectives

- Understand and explore a real-world dataset.
- Perform basic data inspection and cleaning.
- Select input features and target variables.
- Visualize the relationship between features and house prices.
- Build and train a Linear Regression model.
- Evaluate model performance using regression metrics.
- Predict the price for a new input value.

## 📂 Dataset Information

**Dataset Name:** Real Estate Valuation Data Set

**Source:** UCI Machine Learning Repository

**Dataset Link:** https://archive.ics.uci.edu/dataset/477/real+estate+valuation+data+set

**Dataset Details:**
- Total Records: 414
- Total Columns: 8
- Missing Values: 0
- Duplicate Records: 0

### Selected Features

| Variable | Description |
|---|---|
| X (Input) | Distance to the nearest MRT station |
| Y (Target) | House price per unit area |

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## ⚙️ Project Workflow

1. Dataset Selection and Loading
2. Data Inspection and Exploration
3. Data Cleaning
4. Feature and Target Selection
5. Data Visualization using Scatter Plot
6. Training and Testing Split (80:20)
7. Linear Regression Model Training
8. House Price Prediction
9. Model Evaluation
10. Actual vs Predicted Visualization
11. New House Price Prediction

## 📊 Model Evaluation Results

| Evaluation Metric | Result |
|---|---:|
| MAE | 6.92097 |
| MSE | 77.34399 |
| RMSE | 8.79454 |
| R² Score | 0.53896 |

The model achieved an R² score of approximately 0.539, meaning it explains about 53.9% of the variation in the target variable on the test data.

## 🔮 New House Price Prediction

- Distance to nearest MRT station: 1000 meters
- Predicted price per unit area: 38.8333

**Note:** The target values are measured in 10,000 New Taiwan Dollars per Ping, not Indian Rupees.

## 💻 How to Run the Project

1. Clone or download this repository.
2. Open the `.ipynb` notebook using Google Colab.
3. Upload the Excel dataset when prompted.
4. Run all the
