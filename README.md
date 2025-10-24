# 🏠 House Price Prediction

This project predicts house prices using machine learning algorithms based on features such as the number of bedrooms, condition, area, and other property attributes.  
It involves data cleaning, exploratory data analysis, and model training using **Linear Regression** and **Decision Tree Regressor**.

---

## 📊 Project Overview
The main objective of this project is to build and evaluate regression models to predict the price of houses using historical housing data.

The project includes:
- Loading and preprocessing the dataset  
- Exploratory Data Analysis (EDA) with visualizations  
- Feature selection and data splitting  
- Model training and evaluation using metrics such as MAE, MSE, and RMSE  

---

## 🧠 Machine Learning Models Used
- **Linear Regression**
- **Decision Tree Regressor**

Both models were trained and compared to evaluate performance in predicting house prices.

---

## 🧰 Technologies & Libraries
This project was developed using **Python** and the following libraries:

- `pandas` – Data manipulation and analysis  
- `numpy` – Numerical computations  
- `matplotlib` – Data visualization  
- `scikit-learn` – Machine learning models and metrics  

---

## 📘 Brief Explanation

This project focuses on predicting house prices using **machine learning techniques** based on various property features such as number of bedrooms, condition, area, and other attributes.  

### 🔍 Workflow Summary
1. **Data Loading & Cleaning**  
   The dataset (`house_data.csv`) is imported and cleaned by removing unnecessary columns like `id`, `date`, `lat`, `long`, etc., which don’t contribute significantly to price prediction. Missing values are checked and handled appropriately.

2. **Exploratory Data Analysis (EDA)**  
   Visualizations such as **scatter plots** are used to study the relationship between features (like `condition` vs. `price`). This helps in understanding which factors affect house prices the most.

3. **Feature Selection & Splitting**  
   The target variable (`price`) is separated from the feature set (`X`), and the dataset is split into **training** and **testing** parts using a 70–30 ratio.

4. **Model Training**  
   Two models are trained:
   - **Linear Regression** – to capture linear relationships  
   - **Decision Tree Regressor** – to capture non-linear relationships

5. **Model Evaluation**  
   The models are evaluated using performance metrics:
   - **Mean Absolute Error (MAE)**  
   - **Mean Squared Error (MSE)**  
   - **Root Mean Squared Error (RMSE)**  
   The model’s accuracy on both training and testing sets is also compared.

6. **Results**  
   Both models are able to predict house prices reasonably well, with **Linear Regression** performing as a good baseline model and **Decision Tree Regressor** capturing more complex patterns in the data.

---

## 💬 User Interaction and Output

When running the notebook:
- The program first loads and analyzes the dataset automatically.  
- It displays statistical information and visual insights about housing data.  
- After training the models, it prints evaluation metrics such as:
  ```
  Accuracy on Training Data: ...
  Accuracy on Testing Data: ...
  Mean Absolute Error (MAE): ...
  Mean Squared Error (MSE): ...
  Root Mean Squared Error (RMSE): ...
  ```
- The output helps the user understand how well each model performs.
- Users can modify input data or features in the notebook to see how predictions change.

*(Example)*  
If a user provides details like:
- Number of bedrooms: 3  
- Bathrooms: 2  
- Area: 1800 sq.ft  
- Condition: 4  

The trained model can output an **estimated price** for the house based on learned patterns from the dataset.

---

## 📈 Model Evaluation

The models are evaluated using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

Example output:
```
----- Linear Regression - Model Evaluation -----
Mean Absolute Error (MAE):  ...
Mean Squared Error (MSE):  ...
Root Mean Squared Error (RMSE):  ...
```

---

## 🔮 Future Enhancements
- Include more features (e.g., location, amenities, renovation year)
- Use ensemble models like Random Forest or XGBoost
- Build a web app using Flask or Streamlit for live user input and predictions

---

## 📂 Project Structure
```
house-price-prediction/
│
├── house_price_prediction.ipynb   # Main Jupyter Notebook
└── README.md                      # Project documentation
```

---

## 🏁 Conclusion

This project demonstrates the complete workflow of a **machine learning regression problem** — from data cleaning and analysis to model training and evaluation.  
It shows how user-provided housing details can be used to predict accurate house prices using **Linear Regression** and **Decision Tree Regressor** models.  
The results prove that with good preprocessing and model selection, machine learning can provide valuable insights and reliable predictions in the real estate domain.

---

## 👩‍💻 Author
**Pramithack**  
pramithackoderi@gmail.com


