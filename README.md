# 🚗 Car Price Prediction Machine Learning Model

### Developed a machine learning model to accurately predict car ex-showroom prices based on 140 car attributes, providing valuable insights for informed decision-making in the automotive industry.

## 🌟 Project Overview

In today's rapidly evolving automotive market, determining the appropriate pricing for cars is crucial for striking a balance between affordability for customers and profitability for businesses. By analyzing various car features such as mileage, horsepower, fuel type, and more, this project aims to **predict the ex-showroom price of cars**.

Ex-showroom price refers to the base price of a car before any additional costs like taxes and registration fees are added. This model helps the automotive industry make data-driven decisions about car pricing, ensuring competitiveness and customer satisfaction.

### ⚙️ Goal

The objective of this project is to build a machine learning model that accurately predicts car prices based on various relevant features, enabling businesses and consumers to optimize their strategies in the competitive automotive market.

### 🎯 Purpose

This project provides valuable insights to businesses, helping car buyers and sellers make well-informed decisions. The machine learning model is built by analyzing a **raw dataset with 140 car attributes**.

## 📂 Dataset

- **Source**: The dataset was obtained from **[Kaggle](#)**, consisting of 140 car attributes.


## 🚀 Work Flow

1. **Step 1**: Importing the required libraries.
2. **Step 2**: Loading the dataset.
3. **Step 3**: Basic understanding of the data.
4. **Step 4**: Data Cleaning (handling missing values, outliers).
5. **Step 5**: Exploratory Data Analysis (EDA) and Insights.
6. **Step 6**: Data Preparation for Modeling.
7. **Step 7**: Model Building and Validation.

---

## 🔍 Methodologies and Techniques

- **Feature Selection**: Used `SelectKBest` based on statistical tests, such as ANOVA, to identify the most relevant features.
- **Correlation Analysis**: Performed to understand the relationships between features and target variables.
- **Data Skewness**: Checked and corrected using Box-Cox transformations.
- **Scaling**: Applied Robust Scaling to standardize the data.
- **Model Comparison**: Evaluated different machine learning models for performance.

## 🛠️ Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - NumPy, Pandas (Data Processing)
  - Matplotlib, Seaborn (Data Visualization)
  - Scikit-learn, XGBoost (Modeling) and more.

## ⚡ Model Performance

Overall, the models showed excellent performance, with **tree-based ensemble methods** performing the best. These models captured complex relationships in the data, resulting in high accuracy.

### Top 3 Models:

1. **XGBoost Regressor**: 
   - 🏆 **R² score: 98.7%**
2. **Random Forest Regressor**: 
   - 🥈 **R² score: 98.4%**
3. **Gradient Boosting Regressor**: 
   - 🥉 **R² score: 98.0%**

---

## 📊 Key Insights

- **XGBoost** emerged as the top-performing model with an R² score of **98.7%**, demonstrating its effectiveness in capturing complex interactions in the data.
- Tree-based models like **Random Forest** and **Gradient Boosting** also performed exceptionally well, with scores of **98.4%** and **98.0%** respectively.
- The dataset was cleaned, preprocessed, and reduced to the most significant features, enhancing model accuracy.

---

## 📈 Conclusion

This project successfully predicted car ex-showroom prices using relevant car attributes with a strong predictive performance of **98.7%**. Key highlights include:

- Comprehensive **Data Cleaning** and **Preprocessing** steps to handle missing values, outliers, and inconsistencies.
- Effective **Feature Selection** techniques to identify the most important car attributes.
- Implementation of robust machine learning models, with **XGBoost** proving to be the best performer.


🙌 Acknowledgments
Special thanks to Kaggle for providing the dataset and the community for inspiring this project.



  
