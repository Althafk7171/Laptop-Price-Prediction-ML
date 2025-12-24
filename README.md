# Laptop Price Prediction 💻  
Machine Learning Regression Project

## 📌 Project Overview
This project focuses on building a **machine learning model to predict laptop prices**
based on hardware specifications and categorical attributes such as **brand, processor,
RAM, storage, display quality, GPU, and operating system**.

The goal is to automate laptop price estimation using structured data and identify
the most important factors influencing pricing.

---

## 🗂️ Repository Contents
- `Laptop_Price_Prediction.ipynb` – Jupyter Notebook containing EDA, preprocessing, and model training  
- `laptop_data.csv` – Dataset with laptop specifications  
- `Laptop_Price_Prediction_Report.pdf` – Detailed academic project report  
- `Laptop_Price_Prediction_PPT.pptx` – Presentation summarizing the project  

---

## 🧠 Problem Statement
Laptop pricing depends on many interacting features, making manual price estimation
subjective and inconsistent.  
This project applies **machine learning regression techniques** to predict laptop prices
objectively using historical data.

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Methodology

### Data Preprocessing
- Cleaned numeric columns (RAM, Weight)
- Handled missing values
- Extracted structured features from text columns
- One-Hot Encoded categorical variables
- Applied **log transformation** to the target variable (Price)

### Feature Engineering
- Pixels Per Inch (PPI) from screen resolution and size
- Binary features for Touchscreen and IPS display
- Separate HDD and SSD storage features
- CPU brand categorization

### Exploratory Data Analysis (EDA)
- Price distribution analysis
- Brand-wise and specification-wise price comparison
- Visualization of key relationships

---

## 🤖 Machine Learning Models Used
- Linear Regression with Lasso Regularization  
- K-Nearest Neighbors (KNN) Regressor  
- Random Forest Regressor  

---

## 📊 Model Evaluation
- Train-test split: **85% training / 15% testing**
- Evaluation metrics:
  - R² Score
  - Mean Absolute Error (MAE)

### Best Performing Model
- **Random Forest Regressor**
  - Achieved the highest R² score
  - Effectively captured non-linear feature interactions

---

## 📈 Key Insights
- RAM size, processor type, and display quality strongly influence laptop prices
- Brand reputation significantly impacts pricing
- Log transformation improved model stability
- Ensemble models outperform linear models on complex data

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/laptop-price-prediction.git

