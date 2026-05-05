#  Student Score Prediction using Simple Linear Regression

##  Project Overview

This project explores the relationship between **study hours and student performance**.
Using a custom-built dataset, a **Simple Linear Regression model** is developed to predict student marks based on the number of hours studied.

---

##  Project Objective

The main goal is to verify the assumption that **more study hours lead to higher marks**.

The project follows a complete data science workflow:

* **Data Creation:** Building a custom dataset for uniqueness
* **Exploratory Data Analysis (EDA):** Understanding patterns and relationships
* **Model Building:** Training a Linear Regression model using Scikit-learn
* **Evaluation:** Measuring performance using MAE, MSE, and R² score

---

## The Dataset

The dataset is manually created and slightly modified to meet academic requirements.

* **Feature (X):** Hours Studied
* **Target (Y):** Scores (Marks)
* **Size:** Multiple records representing student performance

### Key Finding from EDA

* Strong **positive correlation** between study hours and scores
* Data follows a **linear trend**, making it suitable for regression

---

## ⚙️ Tech Stack

* **Language:** Python
* **Libraries Used:**

  * Pandas → Data handling
  * NumPy → Numerical operations
  * Matplotlib → Visualization
  * Scikit-learn → Model training & evaluation

---

## 🤖 Model Building

A **Simple Linear Regression model** is trained using 80% of the data and tested on 20%.

The model follows the equation:

y = mx + c

Where:

* **m** = slope (increase in marks per hour studied)
* **c** = intercept

---

##  Model Performance

###  Evaluation Metrics:

* **R² Score:** Indicates how well the model explains the data
* **MAE (Mean Absolute Error):** Average prediction error
* **MSE (Mean Squared Error):** Squared error measure

✔ The model shows a strong linear relationship and good prediction accuracy

---

##  Visualizations

The project includes:

*  **Histogram** → Distribution of hours and scores
* **Scatter Plot** → Relationship between study hours and marks
   **Regression Line Plot** → Model fit visualization
* **Boxplot** → Outlier detection

---

##  How to Run

```bash
git clone https://github.com/your-username/simple-linear-regression-project.git
cd simple-linear-regression-project
pip install pandas numpy matplotlib scikit-learn
```

Run the notebook:

```bash
jupyter notebook regression.ipynb
```



##  Conclusion

The model successfully demonstrates that:

* There is a **strong positive relationship** between study hours and marks
* As study hours increase, scores also increase
* The model can be used for **basic academic performance prediction
