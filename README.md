## 🏠 House Price Prediction using Machine Learning

This project focuses on building regression models to predict house prices based on various features from a housing dataset. It follows a complete machine learning workflow — from data preprocessing and visualization to model evaluation and selection.

### 📌 Key Features

- 📊 **Exploratory Data Analysis (EDA)**:
  - Visualized feature relationships using heatmaps, histograms, scatter plots, and pair plots
  - Identified and treated missing values, outliers, and categorical variables

- 🧹 **Data Preprocessing**:
  - Handled missing data
  - Performed one-hot encoding on categorical features
  - Normalized/standardized numerical features where required

- 🤖 **Model Building & Evaluation**:
  - Trained multiple regression models:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
  - Evaluated models using:
    - Root Mean Squared Error (RMSE)
    - Cross-validation (`cross_val_score`)
    - Feature importance analysis (for tree models)

- 📈 **Model Comparison**:
  - Compared performance across models
  - Selected best model based on validation metrics

### 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

### 📂 Example Use Cases

- Predict house prices for new listings based on features such as number of rooms, location indicators, area, etc.
- Analyze which features influence pricing the most
- Compare multiple regression strategies in a practical setting

