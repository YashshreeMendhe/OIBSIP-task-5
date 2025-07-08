# OIBSIP-task-5
Predicting house prices using Linear Regression on a housing dataset with evaluation metrics.
# 🏠 Task 4: Predicting House Prices with Linear Regression
📌 Task Title: Predicting House Prices using Linear Regression
---
 📊 Objective:
To develop a **Linear Regression Model** that predicts house prices based on various features like area, number of bedrooms, bathrooms, and parking. This task provides practical experience in regression modeling, preprocessing, and model evaluation.
---
📁 Dataset:
- **File:** `Housing.csv`
- **Features:**
  - `area`
  - `bedrooms`
  - `bathrooms`
  - `stories`
  - `parking`
- **Target:** `price`
-----
 🧰 Tools & Libraries Used:
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn
---
🔧 Steps Performed:
1. **Data Loading & Inspection**
   - Read the dataset and explored its structure.
   - Viewed data types, missing values, and summary statistics.

2. **Data Cleaning**
   - Handled missing values.
   - Converted categorical columns using `get_dummies()`.

3. **Feature Selection & Preprocessing**
   - Selected relevant features for prediction.
   - Standardized the features using `StandardScaler`.
   - Split data into training and testing sets.

4. **Model Building**
   - Built a **Linear Regression** model using `LinearRegression()` from `sklearn`.
   - Trained the model with training data.

5. **Model Evaluation**
   - Evaluated using:
     - R² Score
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
   - Plotted Actual vs Predicted Prices.

6. **Output**
   - Exported predictions to a file: `Housing_Predictions.csv`
  ---
 📈 Visualizations:
- Distribution of house prices  
- Heatmap showing correlation  
- Actual vs Predicted plot  
- Residuals distribution plot  
---
 ✅ Conclusion:
This project helped in:
- Understanding linear regression in real-life data
- Data cleaning, transformation, and visualization
- Training and evaluating a regression model effectively
---

📂 **Project Files:**
- `Housing.csv` – Dataset  
- `House_Price_Prediction.ipynb` – Model Code  
- `Housing_Predictions.csv` – Output with predictions  
- `README.md` – Project documentation


