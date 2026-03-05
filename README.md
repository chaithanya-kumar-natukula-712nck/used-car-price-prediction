# 🚗 Used Car Price Prediction

This project builds a **Machine Learning model to predict the selling price of used cars** based on various features such as vehicle age, fuel type, transmission, kilometers driven, and seller type.

The model is trained using the **CarDekho dataset** and multiple regression algorithms are compared to find the best performing model.

---

# 📊 Project Overview

Predicting used car prices is useful for:

* Buyers looking for fair market prices
* Sellers wanting competitive pricing
* Online car marketplaces

This project applies **data preprocessing, feature engineering, model training, and hyperparameter tuning** to build an accurate regression model.

---

# 📂 Dataset

Dataset: **CarDekho Used Car Dataset**

File included in this repository:

```
cardekho_dataset.csv
```

### Features

| Feature           | Description           |
| ----------------- | --------------------- |
| car_name          | Name of the car       |
| model             | Car model             |
| vehicle_age       | Age of the car        |
| km_driven         | Kilometers driven     |
| seller_type       | Dealer or Individual  |
| fuel_type         | Petrol / Diesel / CNG |
| transmission_type | Manual / Automatic    |
| mileage           | Mileage of the car    |
| engine            | Engine capacity       |
| max_power         | Maximum power         |
| seats             | Number of seats       |
| selling_price     | Target variable       |

---

# ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

# 🔄 Project Workflow

### 1️⃣ Data Loading

The dataset is loaded using Pandas.

```python
df = pd.read_csv("cardekho_dataset.csv")
```

---

### 2️⃣ Data Cleaning

* Removed unnecessary columns
* Checked for missing values
* Handled categorical variables

---

### 3️⃣ Exploratory Data Analysis

Performed visualizations including:

* Scatter plots
* Box plots
* Histograms
* Feature distribution analysis

---

### 4️⃣ Feature Engineering

Categorical features were encoded using:

* Label Encoding
* One Hot Encoding

Feature scaling was applied using:

```
StandardScaler
```

---

### 5️⃣ Train Test Split

Dataset split into training and testing sets:

```
80% Training
20% Testing
```

---

# 🤖 Machine Learning Models Used

The following regression models were implemented:

* Linear Regression
* Lasso Regression
* Ridge Regression
* K-Nearest Neighbors
* Decision Tree Regressor
* Random Forest Regressor
* AdaBoost Regressor

---

# ⚡ Hyperparameter Tuning

Hyperparameter tuning was performed using:

```
GridSearchCV
```

Models tuned:

* KNN Regressor
* Random Forest Regressor
* AdaBoost Regressor

---

# 📈 Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

# 🏆 Best Model

After hyperparameter tuning, the **Random Forest Regressor** produced the best performance for predicting car prices.

---

# 📁 Project Structure

```
used-car-price-prediction
│
├── used_car_price_prediction.ipynb
├── cardekho_dataset.csv
└── README.md
```

---

# 🚀 How to Run the Project

Clone the repository:

```
git clone https://github.com/chaithanya-kumar-natukula-712nck/used-car-price-prediction.git
```

Navigate to the project folder:

```
cd used-car-price-prediction
```

Run the notebook:

```
jupyter notebook used_car_price_prediction.ipynb
```

---

# 🎯 Key Learning Outcomes

* Data preprocessing
* Feature engineering
* Regression modeling
* Hyperparameter tuning
* Model evaluation

---

# 👨‍💻 Author

**Chaithanya Kumar Natukula**
B.Tech Computer Science Engineering

