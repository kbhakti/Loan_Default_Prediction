# Predicting Loan Default Using Borrower Information

This project is a part of the AAI-501 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). 

- Project Status: Completed

## How to run the project

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   https://github.com/kbhakti/Loan_Default_Prediction


2. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook Loan_Default_Prediction.ipynb

   
## Objective

This project focuses on predicting loan defaults using machine learning techniques such as Logistic Regression and LightGBM. The goal is to identify patterns in borrower data that distinguish "Good Loans" from "Bad Loans".

## Contributors
Teammates: Bhakti Kanungo, Sabina George, Evin Joy

## 📁 Project Structure

- **Data Preprocessing:** Cleaned and encoded the dataset, handled missing values, and addressed class imbalance.
- **Exploratory Data Analysis:** Visualized relationships between features using violin plots, pairplots, and heatmaps.
- **Model Development:** Built Logistic Regression and LightGBM models to classify loan conditions.
- **Model Evaluation:** Evaluated performance using accuracy, precision, recall, F1-score, and confusion matrices.
- **Insights:** Identified key features influencing loan default risk such as interest rate, FICO score, and loan amount.

## 📊 Key Results

- **Logistic Regression Accuracy:** ~82.8%
- **LightGBM Accuracy:** ~83%
- Good performance on both training and validation datasets
- Model saved using `joblib` for future reuse
   
### DataSet

The dataset used for this project is sourced from [Kaggle's All Lending Club loan data](https://www.kaggle.com/datasets/wordsforthewise/lending-club) dataset. 

## Acknowledgement
We are grateful to present this project after successfully completing it. This project would not have been possible without the guidance, assistance, and suggestions of many individuals. We would like to express our deep sense of gratitude and indebtedness to each and every one who has helped us make this project a success.

We take this opportunity to express our deepest sense of gratitude and sincere thanks to everyone who helped us complete this work successfully. We express our sincere thanks to Dr. Ankur Singh Bist, who has been our guide throughout this course. His mentorship, feedback, and support have been invaluable in shaping this project.
