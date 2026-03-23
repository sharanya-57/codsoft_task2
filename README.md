# codsoft_task2
# 🎬 Movie Rating Prediction (Task-02)

## 📌 Objective
To build a machine learning model that predicts movie ratings based on features like year, votes, duration, genre, and other attributes.

---

## 📊 Dataset
The dataset used is **IMDb Movies India**, which contains information about movies such as:
- Name  
- Year  
- Duration  
- Genre  
- Director  
- Actors  
- Votes  
- Rating  

---

## ⚙️ Workflow

### 🔹 Data Cleaning
- Removed commas from Votes and converted to numeric  
- Extracted Year from text format  
- Cleaned Duration column by removing "min"  
- Handled missing values  

### 🔹 Exploratory Data Analysis (EDA)
- Top 10 Movies  
- Genre Distribution  
- Top Directors by Rating  
- Votes vs Rating Relationship  
- Movies Released per Year  
- High Rated Movies Analysis  
- Duration Trends  
- Average Rating per Genre  

### 🔹 Feature Engineering
- Selected relevant features (Year, Votes, Duration)

### 🔹 Model Building
- Linear Regression model used  

### 🔹 Model Evaluation
- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- R² Score  
- Actual vs Predicted visualization  

---

## 📈 Results
- The model provides reasonable predictions of movie ratings  
- Votes and duration show influence on ratings  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🎯 Conclusion
This project demonstrates how regression techniques can be used to predict movie ratings. It also highlights how data cleaning and EDA help in understanding patterns and improving model performance.

---
