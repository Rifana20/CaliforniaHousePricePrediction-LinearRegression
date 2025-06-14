
# 🏠 California Housing Price Prediction – Linear Regression

This project uses the **California Housing Dataset** to perform **Exploratory Data Analysis (EDA)** and build a **Linear Regression model** to predict house prices based on features like median income, average rooms, and geographic location.

---

## 📌 Project Highlights

- Data exploration with Seaborn, Matplotlib, and Plotly  
- Feature correlation analysis  
- Linear Regression model using scikit-learn  
- Model performance metrics (R² Score, MSE, RMSE)  
- Visualization of Actual vs Predicted Sale Prices  

---

## 🗃 Dataset Description

Dataset Source: `sklearn.datasets.fetch_california_housing()`

| Feature      | Description                              |
|--------------|------------------------------------------|
| MedInc       | Median income in block group             |
| HouseAge     | Median house age                         |
| AveRooms     | Average rooms per household              |
| AveBedrms    | Average bedrooms per household           |
| Population   | Block group population                   |
| AveOccup     | Average house occupancy                  |
| Latitude     | Latitude of the block group              |
| Longitude    | Longitude of the block group             |
| SalePrice    | **Target**: Median house value           |

---

## 📊 EDA & Visualization

- Dataset preview and summary statistics  
- Null value check  
- Pairplot and distribution plots  
- Correlation heatmap  
- Scatter plot: MedInc vs SalePrice  

---

## 🤖 Model Training

- Train-test split: 80/20  
- Linear Regression model from `sklearn`  
- Evaluation metrics:
  - R² Score  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  

---

## 📈 Sample Output

