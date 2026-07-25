# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project focuses on predicting house prices using **Linear Regression**. It demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison with Ridge Regression.

The objective is to build a regression model that accurately predicts house prices based on various property features.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Encode categorical features
- Analyse feature correlations
- Train a Linear Regression model
- Evaluate model performance
- Visualise predictions and residuals
- Analyse feature coefficients
- Compare Linear Regression with Ridge Regression

---

## 📂 Dataset

**Dataset Name:** Enhanced House Price Dataset

### Features

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Age
- City
- Furnishing
- Main Road
- Guest Room
- Basement
- Water Supply
- Air Conditioning
- Preferred Tenant
- Locality Rating

### Target Variable

- **Price**

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading
- Imported the dataset
- Examined its structure
- Checked data types

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics
- Distribution of house prices
- Feature selection discussion

### 3. Data Preprocessing
- Checked for missing values
- Performed One-Hot Encoding for categorical features

### 4. Correlation Analysis
- Generated a correlation matrix
- Visualised relationships using a heatmap

### 5. Train-Test Split
- Split the dataset into:
  - 80% Training Data
  - 20% Testing Data

### 6. Model Training
- Built a Linear Regression model using Scikit-learn

### 7. Model Evaluation
The model was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 8. Visualisations
- Actual vs Predicted Scatter Plot
- Residual Plot
- Coefficient Analysis

### 9. Bonus
Compared the performance of:
- Linear Regression
- Ridge Regression

---

## 📈 Results

The Linear Regression model successfully learned the relationship between the house features and the target variable.

Model performance was evaluated using:
- MSE
- RMSE
- R² Score

The Ridge Regression model produced a slightly lower RMSE while maintaining a similar R² Score, indicating a small improvement in prediction accuracy.

---

## 📷 Project Visualisations

The project includes the following visualisations:

- Correlation Heatmap
- Actual vs Predicted Scatter Plot
- Residual Plot
- Feature Coefficient Plot
- Linear Regression vs Ridge Regression Comparison

---

## 📁 Project Structure

```
House-Price-Prediction-Linear-Regression/
│
├── House_Price_Prediction.ipynb
├── house_price_dataset.csv
├── README.md
├── requirements.txt
│
└── images/
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    ├── residual_plot.png
    ├── coefficient_analysis.png
    └── ridge_vs_linear.png
```

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction-Linear-Regression.git
```

### 2. Navigate to the Project Folder

```bash
cd House-Price-Prediction-Linear-Regression
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **House_Price_Prediction.ipynb** and run all cells.

---

## 📚 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🎓 Key Learnings

- Data preprocessing techniques
- Feature engineering
- One-Hot Encoding
- Correlation analysis
- Linear Regression
- Ridge Regression
- Model evaluation
- Residual analysis
- Feature importance interpretation

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Lasso Regression
- Elastic Net Regression
- Cross Validation
- Feature Scaling
- Random Forest Regressor
- XGBoost Regressor

---

## 👩‍💻 Author

**Pallavi Sagar**

---

## ⭐ If you found this project helpful, consider giving it a star!
