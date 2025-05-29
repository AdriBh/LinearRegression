# 🏡 House Price Prediction using Linear Regression

This project uses **Simple and Multiple Linear Regression** techniques to predict house prices based on various features such as area, number of bedrooms, furnishing status, and more. It demonstrates how to preprocess data, apply regression, evaluate performance, and interpret model outputs.

---

## 📁 Dataset

The dataset contains housing data with the following features:

| Feature               | Description                                           |
|-----------------------|-------------------------------------------------------|
| `area`                | Area of the house in square feet                      |
| `bedrooms`            | Number of bedrooms                                    |
| `bathrooms`           | Number of bathrooms                                   |
| `stories`             | Number of floors                                      |
| `mainroad`            | Whether the house is on a main road (`yes`/`no`)      |
| `guestroom`           | Presence of guest room (`yes`/`no`)                   |
| `basement`            | Whether the house has a basement                      |
| `hotwaterheating`     | Availability of hot water heating                     |
| `airconditioning`     | Whether the house has air conditioning                |
| `parking`             | Number of parking spaces                              |
| `prefarea`            | Is the house in a preferred area                      |
| `furnishingstatus`    | Furnishing status (`furnished`, `semi-furnished`, `unfurnished`) |
| `price`               | **Target variable** – selling price of the house      |

Some categorical features are label-encoded, and the price is log-transformed to reduce skewness.

---

## 🔧 Technologies Used

- Python 🐍
- NumPy & Pandas
- Scikit-learn (LinearRegression, preprocessing, metrics)
- Matplotlib & Seaborn for data visualization

---

## 📈 Approach

1. **Data Preprocessing**
   - Label encoding of categorical variables
   - Normalization using `MinMaxScaler`
   - Log transformation of target (`price`)

2. **Modeling**
   - Simple Linear Regression (e.g., using `area` only)
   - Multiple Linear Regression (using all relevant features)
   - Performance evaluation: MSE, MAE, and R² score

3. **Visualization**
   - Distribution of target variable before/after log transformation
   - Regression line plots for each feature
   - Residual analysis

---

## 📊 Results

- The model performs reasonably well on this structured dataset.
- Right-skewed `price` distribution is effectively handled using log transformation.
- Multiple regression outperforms simple regression in capturing house price patterns.

---

## 📁 Dataset

The dataset used for this project is publicly available on Kaggle:

🔗 **[House Price Prediction Dataset](https://www.kaggle.com/datasets/ujjwalchowdhury/house-price-prediction-dataset)**  
➡️ https://www.kaggle.com/datasets/ujjwalchowdhury/house-price-prediction-dataset

