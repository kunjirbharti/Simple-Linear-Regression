#  Simple Linear Regression Project

##  Introduction

This project demonstrates **Simple Linear Regression** using Python.
The objective is to analyze and predict student performance (**Scores**) based on study hours (**Hours**) using a custom dataset.

---

##  Problem Statement

To build a predictive model that estimates student marks based on the number of hours studied and to understand the relationship between these two variables.

---

##  Dataset

* File: `score_updated.csv`
* Type: Custom dataset (created/modified for uniqueness)

### Features:

* **Hours** → Number of hours studied (Independent Variable)
* **Scores** → Marks obtained (Dependent Variable)

✔ Dataset has been prepared as per academic requirements to ensure originality.

---

##  Exploratory Data Analysis (EDA)

Performed initial analysis to understand the dataset:

* Checked dataset shape, columns, and data types
* Verified missing values and duplicates
* Generated statistical summary
* Visualized data using:

  * Scatter plot
  * Histogram
  * Boxplot
* Checked correlation between variables

###  Key Insights:

* No missing values found
* No duplicate records
* Strong positive correlation between Hours and Scores
* Data shows a linear trend suitable for regression

---

##  Methodology

The project uses the linear regression equation:

y = mx + c

Where:

* **m (slope)** → rate of change of scores with respect to hours
* **c (intercept)** → predicted score when hours = 0

---

##  Implementation Steps

1. Import libraries
2. Load dataset
3. Perform EDA
4. Split data into training and testing sets
5. Train model using `LinearRegression`
6. Make predictions
7. Visualize regression line
8. Evaluate model performance

---

##  Model Evaluation

The model is evaluated using:

* **MAE (Mean Absolute Error)**
* **MSE (Mean Squared Error)**
* **R² Score (Coefficient of Determination)**

✔ R² score indicates how well the model fits the data.

---

##  Results

* A regression line is fitted to the dataset
* The model shows a **strong positive relationship** between study hours and scores
* Predictions are reasonably accurate

---

##  Visualization

* Scatter plot of actual data points
* Regression line showing predicted values


##  Conclusion

* Simple Linear Regression effectively models the relationship between study hours and scores
* As study hours increase, marks tend to increase
* The model can be used for basic predictive analysis

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
