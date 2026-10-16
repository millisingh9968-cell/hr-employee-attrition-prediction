# HR Employee Attrition Prediction

A beginner-friendly machine learning project demonstrating an end-to-end HR employee attrition prediction pipeline using Python and Scikit-learn.

## Project Overview
This project explores how machine learning can classify whether an employee may resign within the following year. It uses automatically generated synthetic HR data to demonstrate data preparation, model development, evaluation, and responsible interpretation.

## Objectives
- Generate and inspect synthetic HR employee data.
- Clean missing values and duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Apply feature preprocessing, scaling, and categorical encoding.
- Handle class imbalance using SMOTENC.
- Train and compare Logistic Regression models.
- Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices.
- Save model components and evaluation results.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- imbalanced-learn
- Joblib
- Google Colab / Jupyter Notebook

## Project Workflow
1. Data generation and loading
2. Data quality inspection
3. Data cleaning and validation
4. Feature selection and train-test splitting
5. Exploratory data analysis
6. Missing-value imputation
7. Numerical feature scaling
8. Class imbalance handling with SMOTENC
9. Categorical feature encoding
10. Logistic Regression model training
11. Model evaluation and comparison
12. Prediction for a fictional employee
13. Saving model components and outputs

## Dataset
The notebook generates 1,000 fictional employee records and adds 20 duplicate rows for cleaning practice. It includes features such as department, work mode, experience, monthly salary, satisfaction, overtime, and absences.

**Note:** The dataset is synthetic and contains no real employee records.

## How to Run
1. Clone or download this repository.
2. Open `HR_Attrition_Monday_Complete_Pipeline.ipynb` in Google Colab or Jupyter Notebook.
3. Run the notebook cells sequentially.
4. Review the generated visualizations, evaluation metrics, and saved outputs.

## Model Evaluation
The project compares a baseline Logistic Regression model with a model trained using SMOTENC oversampling. Both models are evaluated on the same untouched test set.

Actual evaluation scores should be added after running the notebook.

## Responsible Use and Limitations
This is an educational project, not a production-ready HR decision system. Predictions must not be treated as proof that an employee will resign or as evidence of why they might leave. Real-world use would require representative data, privacy safeguards, fairness testing, validation, and human oversight.

## Author
Add your name here.

## License
Add a license if you intend to distribute or reuse this project publicly.
