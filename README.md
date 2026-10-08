# CodeAlpha Credit Scoring Model

## Project Overview

This project uses machine learning to predict whether a loan applicant has good or bad credit risk. It was developed as part of the CodeAlpha Machine Learning Internship.

## Dataset

The project uses the German Credit dataset (`german.data`), containing 1,000 records and 20 input features.

* **Good Credit:** 700 records
* **Bad Credit:** 300 records

## Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Support Vector Machine (SVM)
4. Tuned Random Forest

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Project Workflow

1. Load and explore the dataset.
2. Prepare the target variable.
3. Split data into training and testing sets.
4. Preprocess numerical and categorical features.
5. Train machine learning models.
6. Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrices.
7. Compare the models.

## Results

| Model               | Accuracy |
| ------------------- | -------: |
| Logistic Regression |      78% |
| Decision Tree       |      57% |
| SVM                 |      76% |
| Tuned Random Forest |      77% |

The SVM model achieved approximately 76.7% recall for bad-credit applicants in the test set.

## How to Run

1. Install Python.
2. Install the required libraries:
   `pip install pandas scikit-learn matplotlib jupyter`
3. Open `Credit_Scoring_Model.ipynb` in VS Code or Jupyter Notebook.
4. Run the notebook cells from top to bottom.

## Disclaimer

This project is for educational purposes. Its predictions should not be used as the sole basis for real financial or lending decisions.
