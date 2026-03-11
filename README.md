# 🚗 BMW Car Price Prediction using Machine Learning

This project performs **Exploratory Data Analysis (EDA)** and builds a **Machine Learning pipeline** to predict BMW car prices using a dataset from Kaggle.

The notebook demonstrates a complete **end-to-end data science workflow**, including data cleaning, visualization, preprocessing, model training, and evaluation.

---

# 📊 Dataset

Dataset Source: **Kaggle – BMW Cars Market Dataset**

The dataset contains information about BMW cars such as:

- Model
- Mileage
- Year
- Transmission
- Fuel type
- Engine size
- Price

Target variable:
- Price_usd

---

# 🧠 Project Workflow

The project follows a standard **Machine Learning pipeline**:

### 1️⃣ Data Loading
- Load dataset using **Pandas**

### 2️⃣ Data Cleaning
- Remove duplicate records
- Handle missing values

### 3️⃣ Exploratory Data Analysis (EDA)
- Dataset summary statistics
- Distribution plots
- Correlation heatmap

### 4️⃣ Feature Engineering
- Identify numerical and categorical features

### 5️⃣ Data Preprocessing
Using **Scikit-learn pipelines**

- StandardScaler for numerical features
- OneHotEncoder for categorical features

### 6️⃣ Model Training
Two machine learning models are trained:

- **Linear Regression**
- **Random Forest Regressor**

### 7️⃣ Model Evaluation

Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📈 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Project Structure
BMW-Car-Price-Prediction
│
├── bmw_cars.csv
├── bmw_price_prediction.ipynb
├── README.md


---

# ⚙️ Installation

Clone the repository:
git clone https://github.com/yourusername/BMW-Car-Price-Prediction.git


---

# 📊 Example Results

The models are evaluated using standard regression metrics.

Example output:
<img width="1180" height="352" alt="image" src="https://github.com/user-attachments/assets/aeede4d4-8642-4c42-b896-636381414290" />
<img width="1179" height="340" alt="image" src="https://github.com/user-attachments/assets/4acb86b4-9fdd-4fb1-828b-b7e560f396d8" />

Random Forest typically performs better because it can capture **non-linear relationships in the data**.

---

# 🎯 Learning Objectives

This project demonstrates:

- Real-world **EDA techniques**
- **Feature preprocessing pipelines**
- **Machine Learning model training**
- **Model evaluation metrics**
- Building a **complete data science workflow**

---

# 📌 Future Improvements

Possible enhancements:

- Hyperparameter tuning
- Feature importance analysis
- Model comparison with XGBoost / Gradient Boosting
- Deployment using Flask or FastAPI
- Interactive dashboard using Streamlit

---

# 👨‍💻 Author

**Gulfam Hussain**

Master's Student in Data Science  
Interested in **Data Analytics, Machine Learning, and AI**

---

# ⭐ If you like this project

Give this repository a **star ⭐ on GitHub**
