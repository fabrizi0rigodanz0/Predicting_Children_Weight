# Predicting Children's Weight Based on Age

## Project Description
This project involves predicting the weight of children up to 24 months old based on their age. The dataset used is from the National Health and Nutrition Examination Survey (NHANES) of 2017-2018. The primary goal is to develop regression models that can accurately predict children's weight using age as the input variable.

## Project Objectives
1. **Data Visualization:** Understand the relationship between age and weight through scatter plots.
2. **Linear Regression Model:** Build and evaluate a linear regression model to predict weight.
3. **Polynomial Regression Models:** Explore polynomial regression models of different degrees to find the best fit.

## Dataset
The dataset `children.csv` contains two columns:
- `age`: Age of the child in months.
- `weight`: Weight of the child in kilograms.

## Methodology
1. **Data Loading and Preprocessing:** Import necessary libraries and load the dataset.
2. **Exploratory Data Analysis (EDA):** Visualize the data to identify trends and correlations.
3. **Linear Regression:**
   - Plot data and calculate correlation.
   - Build a linear regression model and evaluate its performance using cross-validation.
4. **Polynomial Regression:**
   - Evaluate polynomial models of degrees 1 through 10.
   - Select the best model based on cross-validation scores.
   - Find and display the coefficients of the best polynomial model.

## Results
1. **Linear Regression Model:**
   - Correlation between age and weight: 0.88
   - Model equation: `weight = 0.33 * age + 5.7`
2. **Polynomial Regression Model:**
   - Best degree: 10
   - Model coefficients: Detailed in the notebook

## Visualizations
- Scatter plots showing the relationship between age and weight.
- Regression lines for both linear and polynomial models.

## How to Run the Project
1. Clone the repository.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install necessary libraries: `pandas`, `scikit-learn`, `matplotlib`.
4. Open the Jupyter Notebook and run all cells.
