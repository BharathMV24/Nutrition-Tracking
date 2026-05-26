# NutriPredict: Machine Learning-Based Calorie Estimation System

## Project Overview
NutriPredict is a data-driven application designed to analyze dietary habits and estimate caloric content. By utilizing a dataset of common food items, this project leverages machine learning to predict the total calories in a meal based on its macronutrient composition (Protein, Carbohydrates, Fat, and Fiber).

## Key Features
* **Data Preprocessing:** Cleans and normalizes raw dietary logs, handling missing values and structural inconsistencies to ensure reliable analysis.
* **Exploratory Data Analysis (EDA):** Uses visualization to uncover nutritional trends, such as the relationship between macronutrients and caloric density.
* **Predictive Modeling:** Implements a Linear Regression model trained to forecast caloric intake.
* **Performance Evaluation:** Uses standard metrics (R-squared and Mean Squared Error) to measure the predictive accuracy of the model.

## Technologies Used
* **Languages:** Python
* **Libraries:** * `pandas` & `numpy` (Data manipulation)
    * `matplotlib` & `seaborn` (Data visualization)
    * `scikit-learn` (Machine learning and model evaluation)

## Visualizations
This project provides clear insights into nutritional data through:
* **Correlation Heatmaps:** To identify which nutrients have the strongest relationship with calories.

* **Macronutrient Distributions:** Histograms showing the data distribution.
* **Boxplots:** Analyzing variance in calories across different meal types.


## How to Run
1. **Clone the repository:**
   `git clone https://github.com/yourusername/NutriPredict.git`
2. **Install dependencies:**
   `pip install pandas numpy matplotlib seaborn scikit-learn`
3. **Run the Analysis:** Place your `daily_food_nutrition_dataset.csv` in the root folder and execute the provided Jupyter Notebook.

## Project Outcome
This project demonstrates the application of supervised learning in the health and wellness sector, moving from simple data tracking to intelligent, predictive health analysis.

---
*Created by [Bharath M V]*
