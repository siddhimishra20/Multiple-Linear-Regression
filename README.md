# **Multiple Linear Regression: Startup Profit Prediction**  
This project demonstrates the use of **Multiple Linear Regression** to predict the profit of startups based on factors like R&D Spend, Administration, Marketing Spend, and State. By modeling these relationships, we created a regression model that provides insights into how different features influence profitability.

## **🛠 Technologies Used**  
**Programming Language:** Python  
**Libraries:**  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

## **📊 Project Overview**  
- **Goal:** Predict startup profits based on multiple independent variables.  
- **Dataset:** Contains data for 50 startups with features:  
  - R&D Spend  
  - Administration  
  - Marketing Spend  
  - State (categorical)  
  - Profit (dependent variable)  
- **Data Split:**  
  - **Training Set:** 80% of the data.  
  - **Test Set:** 20% of the data.  

## **🔑 Key Learnings**  
- **Understanding Multiple Regression:**  
  - Modeled the relationship between a dependent variable and multiple independent variables using the equation:  
    **𝑦 = 𝑏₀ + 𝑏₁𝑥₁ + 𝑏₂𝑥₂ + ... + 𝑏ₙ𝑥ₙ.**  

- **Data Preprocessing:**  
  - Encoded the categorical variable **State** using **OneHotEncoder**.  
  - Ensured the dataset avoided the dummy variable trap.  

- **Model Training:**  
  - Built and trained the regression model using **Scikit-learn**.  
  - Utilized **NumPy** and **Pandas** for data manipulation.  

- **Visualization:**  
  - Created plots using **Matplotlib** to understand feature relationships and model performance.  

---

## **🚀 Results**  
- Successfully developed a model to predict startup profits with good accuracy.  
- Gained insights into the influence of different features, especially the impact of **R&D Spend**, on profitability.  
- Highlighted the importance of encoding categorical data and splitting datasets for unbiased evaluation.
