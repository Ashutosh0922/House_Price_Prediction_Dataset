# House_Price_Prediction_Dataset


# 📚 Linear Regression Task 

This project implements **Simple and Multiple Linear Regression** using **Scikit-learn**, **Pandas**, and **Matplotlib**.

---

## 🛠️ Steps Followed:

### 1. 📥 Import and Preprocess the Dataset
* Loaded the `Housing.csv` file using **Pandas**.
* Checked for missing values and basic information.
* Converted categorical variables (if any) into numerical format using **one-hot encoding**.

---

### 2. ✂️ Split Data into Train-Test Sets
* Separated features (**X**) and target (**y**).
* Split the dataset into **80% Training** and **20% Testing** using **train_test_split**.

---

### 3. 🤖 Fit a Linear Regression Model
* Initialized the **LinearRegression** model from **sklearn**.
* Trained the model on the training data (`X_train`, `y_train`).

---

### 4. 📊 Evaluate the Model
* Predicted the values on test data.
* Calculated the following metrics:
  - **Mean Absolute Error (MAE)** ✅
  - **Mean Squared Error (MSE)** ✅
  - **R² Score (Accuracy)** ✅

---

### 5. 🖌️ Plot the Regression Line
* Plotted **Actual vs Predicted** values.
* Visualized the **regression line** for better understanding.
* Displayed the **coefficients** and **intercept** of the trained model to interpret the relationship between features and price.

---

## 📦 Tools and Libraries Used
* **Python 3**
* **Pandas** 🐼
* **Scikit-learn** 🔥
* **Matplotlib** 📈

---


