# Molecular Solubility Prediction using Linear Regression

##  Overview

This project builds a **Linear Regression model** to predict the solubility of chemical compounds (`logS`) based on molecular descriptors.

The goal is to understand how different chemical features influence solubility and evaluate how well a simple linear model can capture this relationship.

---

##  Workflow

### 1. Data Loading

* Dataset containing molecular descriptors and solubility values was loaded using Pandas

### 2. Data Preparation

* Features (`X`) and target variable (`y`) were separated
* Target variable: **logS (solubility)**

### 3. Train-Test Split

* Data split into:

  * **80% training set**
  * **20% testing set**
* Ensures model is evaluated on unseen data

### 4. Model Training

* Model used: **Linear Regression**
* The model learns relationships between descriptors and solubility

### 5. Prediction

* Predictions made on both:

  * Training data
  * Testing data

### 6. Evaluation Metrics

* **Mean Squared Error (MSE)** → measures prediction error
* **R² Score** → measures how well the model explains variance

---

##  Data Visualization

* Scatter plot created to compare:

  * Actual values vs Predicted values
* Helps visually assess model performance
* Ideal model would show points along a straight diagonal line

---

##  Results

* Model shows a reasonable fit between predicted and actual values
* Some variation exists, indicating prediction error
* Performance differs between training and testing data

---

##  Limitations

* Linear Regression assumes a linear relationship
* May not capture complex patterns in data
* No feature scaling or advanced preprocessing applied

---

##  Future Improvements

* Add more data visualization (correlation plots, distributions)
* Try advanced models:

  * Polynomial Regression
  * Random Forest
* Apply feature scaling and selection
* Perform hyperparameter tuning

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

##thanks.
