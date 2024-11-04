# Stroke Prediction using Healthcare Dataset

This project analyzes a healthcare dataset related to stroke data and builds a predictive model to identify the likelihood of stroke occurrences. The analysis and modeling are conducted using a Jupyter Notebook environment, with logistic regression chosen as the modeling technique due to its effectiveness in binary classification tasks.

## Dataset

- **Dataset Name:** Healthcare Stroke Dataset
- **Description:** Contains information about various health indicators and demographics that may contribute to stroke risk. 
- **Features:** Includes variables such as age, gender, hypertension, heart disease, marital status, average glucose level, BMI, smoking status, and other relevant attributes.

## Project Overview

1. **Data Preprocessing**
   - Loaded and cleaned the dataset.
   - Managed missing values, particularly in the BMI and other relevant columns.
   - Transformed categorical variables into numerical formats to prepare data for modeling.
   - Normalized continuous variables to improve model performance.

2. **Exploratory Data Analysis (EDA)**
   - Performed statistical analysis and visualizations to understand relationships between features and stroke occurrences.
   - Used graphs and correlation matrices to explore trends and correlations among variables.

3. **Modeling**
   - Built a logistic regression model as it is suitable for binary classification (stroke or no stroke).
   - Split the data into training and testing sets for model evaluation.
   - Optimized model parameters to improve accuracy.

4. **Model Evaluation**
   - Evaluated the model using accuracy, precision, recall, and F1-score metrics.
   - Used a confusion matrix to analyze true positives, false positives, and overall performance.

## Results

- The logistic regression model performed effectively in predicting the likelihood of a stroke.
- Achieved a satisfactory level of accuracy, with evaluation metrics indicating the model's reliability.

## Usage

To replicate this analysis:

1. **Install Requirements:** Ensure Python and Jupyter Notebook are installed. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
   
2. **Run the Notebook:** Open the Jupyter Notebook file and run each cell to follow the analysis and modeling steps.

## Conclusion

This project demonstrates a straightforward approach to using logistic regression for stroke prediction, providing valuable insights for healthcare applications in predictive modeling.
