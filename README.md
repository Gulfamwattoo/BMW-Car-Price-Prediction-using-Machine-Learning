🚗 BMW Cars Market Analysis and Price Prediction

Dataset source: Kaggle – BMW Cars Market Dataset

This project demonstrates a complete Exploratory Data Analysis (EDA) and Machine Learning workflow using a BMW cars dataset. The goal is to analyze the data and build models that can accurately predict the price of BMW cars based on various features.

The notebook covers the full data science pipeline, including data loading, cleaning, visualization, preprocessing, model training, and evaluation.

📊 Project Workflow

This notebook demonstrates:

Data loading using Pandas

Data cleaning and handling missing values

Exploratory Data Analysis (EDA)

Feature preprocessing using Scikit-learn

Training machine learning models

Model performance evaluation

📂 Dataset

The dataset contains information about BMW cars available in the market. Important features include:

Model

Year

Mileage

Transmission

Fuel Type

Engine Size

Price

The target variable in this project is:

price
📈 Exploratory Data Analysis

Several visualizations were created to understand the dataset:

Histogram plots for numerical feature distributions

Correlation heatmap to analyze relationships between variables

Price distribution analysis

EDA helps identify patterns, trends, and relationships in the dataset before building machine learning models.

⚙️ Machine Learning Pipeline

The project uses Scikit-learn pipelines to combine preprocessing and model training steps.

Feature Preprocessing

Two types of features were processed:

Numerical Features

Standardized using StandardScaler

Categorical Features

Encoded using OneHotEncoder

A ColumnTransformer was used to apply transformations to the correct feature types.

🤖 Models Used

Two regression models were trained:

Linear Regression

A baseline regression model used to establish a simple relationship between features and car price.

Random Forest Regressor

An ensemble learning method that improves prediction accuracy by combining multiple decision trees.

📊 Model Performance
Linear Regression

MAE: 4843.62
RMSE: 7142.49
R² Score: 0.945

Random Forest

MAE: 3390.52
RMSE: 4772.16
R² Score: 0.976

The Random Forest model performed better, achieving lower prediction errors and a higher R² score.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📂 Project Structure
BMW-Car-Price-Prediction
│
├── bmw_cars.csv
├── BMW_EDA_ML.ipynb
└── README.md
🎯 Conclusion

This project demonstrates a typical machine learning workflow for a regression problem. The analysis shows that ensemble models like Random Forest can capture complex patterns in the dataset and produce more accurate predictions compared to simple linear models.

👨‍💻 Author

Gulfam Hussain
Master’s Student in Data Science
