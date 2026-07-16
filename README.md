# 🚗 Car Price Analysis and Prediction

A Machine Learning project that analyzes car market data and predicts the selling price of a car based on its features. This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

---

## 📌 Project Overview

The objective of this project is to predict the selling price of a used car using machine learning algorithms. The project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation
- Price Prediction

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Pickle

---

## 📂 Project Structure

```
car-price-analysis/
│
├── app/
│   └── car_price_predictor_app.py
│
├── data/
│   ├── cars_dataset.csv
│   └── cleaned_cars_dataset.csv
│
├── saved_models/
│   ├── DecisionTreeRegressor.pkl
│   ├── LinearRegression.pkl
│   ├── RandomForestRegressor.pkl
│   ├── Ridge.pkl
│   ├── Lasso.pkl
│   └── SVR.pkl
│
├── saved_scaling/
│   └── scaler.pkl
│
├── main.ipynb
├── car_price.sql
├── requirements.txt
├── README.md
├── .gitignore
└── .vscode/
```

---

## 📊 Machine Learning Workflow

1. Import Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Price Prediction

---

## 📈 Features Used

- Car Name
- Year
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

---

## 📉 Model Evaluation

The model was evaluated using regression metrics such as:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/mariyamperveen/car-price-analysis.git
```

### Move to Project Directory

```bash
cd car-price-analysis
```

### Create Conda Environment

```bash
conda create -n carPriceVenv python=3.10
```

### Activate Environment

```bash
conda activate carPriceVenv
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/mariyamperveen/car-price-analysis.git
```

### Step 2: Move to the Project Directory

```bash
cd car-price-analysis
```

### Step 3: Create the Conda Environment

```bash
conda create -n carPriceVenv python=3.10
```

### Step 4: Activate the Environment

```bash
conda activate carPriceVenv
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Run the Streamlit Application

```bash
streamlit run app/car_price_predictor_app.py
```

The application will open automatically in your browser.

---

## 📓 Run the Notebook (Optional)

To explore the data analysis and model training:

```bash
jupyter notebook
```

Open **main.ipynb** and run all the cells.
## 📊 Results

The trained machine learning model predicts the estimated selling price of a used car based on the provided input features. Data visualization and exploratory analysis help identify important factors affecting car prices.

---

## 📚 Future Improvements

- Hyperparameter Tuning
- Streamlit Web Application
- Model Deployment
- Feature Selection
- Additional Regression Models

---

## 👩‍💻 Author

**Mariyam Perveen**

B.Tech (Artificial Intelligence & Data Science)

GitHub: https://github.com/mariyamperveen

---

## ⭐ If you found this project useful, consider giving it a Star.