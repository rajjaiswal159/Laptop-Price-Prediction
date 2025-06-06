# 💻 Laptop Price Prediction 

This project aims to predict the price of laptops using regression models. The dataset contains various specifications of laptops such as processor, RAM, storage, GPU, and more. After preprocessing and feature engineering, an optimized model is built to predict prices with high accuracy.

## 📊 Project Overview

- **Goal**: Predict laptop prices based on specifications.
- **Techniques Used**:
  - Data cleaning and preprocessing
  - Feature engineering
  - Log transformation of target
  - Outlier handling
  - Model used - XGBoost
  - Pipeline creation and hyperparameter tuning


## 🔧 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- XGBoost
- Jupyter Notebook


## 📌 Key Highlights

- Used `.str` accessor for parsing features like CPU, GPU, and screen resolution.
- Extracted and engineered important features such as:
  - `Is_Touchscreen`, `Resolution`, `Processor_Type`, etc.
- Applied `log1p` transformation on the target variable to normalize price distribution.
- Used pipeline and `ColumnTransformer` for scalable preprocessing and modeling.
- Filtered extreme high-price laptops to reduce error due to outliers.

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/laptop-price-prediction.git
   cd laptop-price-prediction
   
2. Install dependencies:
   pip install -r requirements.txt
   
3. Open the notebook::
   jupyter notebook notebook/laptop_price.ipynb
