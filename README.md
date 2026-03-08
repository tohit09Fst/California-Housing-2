# 🏠 House Price Prediction using Machine Learning

This project focuses on predicting housing prices using the **California Housing Dataset**.  
It demonstrates the complete **Machine Learning workflow**, including data preprocessing, feature engineering, model training, and performance comparison.

---

## 📌 Project Objective

The goal of this project is to build and evaluate multiple regression models to predict housing prices and compare their performance.

Key tasks performed:

- Data exploration and visualization
- Feature engineering
- Feature scaling
- Model training
- Model evaluation
- Performance comparison

---

## 📊 Dataset

The dataset used is the **California Housing Dataset**, which contains housing-related information collected from the 1990 California census.

### Features

- **MedInc** – Median income in the area  
- **HouseAge** – Median house age  
- **AveRooms** – Average number of rooms  
- **AveBedrms** – Average number of bedrooms  
- **Population** – Population in the block group  
- **AveOccup** – Average occupancy per household  
- **Latitude** – Geographic latitude  
- **Longitude** – Geographic longitude  

### Target Variable

- **Housing Value** – Median house value in the area

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

## ⚙️ Feature Engineering

To improve model performance, additional features were created:

- Rooms per Household
- Bedrooms per Room
- Population per Household

Feature scaling was applied using **StandardScaler**.

---

## 🤖 Machine Learning Models

The following regression models were implemented:

1. Linear Regression
2. Ridge Regression
3. Decision Tree Regressor
4. Random Forest Regressor

---

## 📈 Model Performance

| Model | R² Score | RMSE |
|------|------|------|
| Linear Regression | 0.653 | 0.673 |
| Ridge Regression | 0.652 | 0.674 |
| Decision Tree | 0.600 | 0.723 |
| Random Forest | **0.774** | **0.544** |

### Best Model
**Random Forest Regressor** achieved the highest performance with:

- **R² Score ≈ 0.77**
- **RMSE ≈ 0.54**

This indicates that the model explains approximately **77% of the variance in housing prices**.

---

## 📊 Visualization

The project includes several visualizations such as:

- Correlation heatmap
- Actual vs predicted values
- Model performance comparison charts
- Residual analysis

---

## 📂 Project Structure
```
project-folder
│
├── task2_feature_engineering.ipynb
├── dataset
│ └── california_housing.csv
├── images
│ └── plots
├── README.md
```


---

## 📚 Key Learnings

Through this project, the following machine learning concepts were explored:

- Exploratory Data Analysis (EDA)
- Feature engineering
- Feature scaling
- Model training and evaluation
- Regression algorithms
- Ensemble learning with Random Forest

---

## 🚀 Future Improvements

Possible improvements include:

- Hyperparameter tuning
- Cross-validation
- Gradient Boosting models
- Advanced feature engineering

---

README.md :
- task1_ml_linear_regression.ipynb
- task2_feature_engineering_model_comparison.ipynb
