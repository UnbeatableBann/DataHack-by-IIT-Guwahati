# DataHack-by-IIT-Guwahati
# Predictive Modeling for Vaccine Uptake

## Overview
This project aims to build a predictive model to determine the likelihood of individuals receiving two types of vaccines: XYZ and seasonal vaccines. The model uses a dataset provided by IIT Guwahati's DataHack competition, focusing on multilabel classification to predict the probabilities of vaccine uptake.

## Contents
1. **Data Description**: Overview of the dataset used in the project.
2. **Preprocessing**: Details on how missing values were handled and features were prepared for modeling.
3. **Modeling**: Explanation of the machine learning techniques used, including the choice of algorithms and evaluation metrics.
4. **Results**: Performance metrics such as ROC AUC scores and insights derived from the model predictions.
5. **Submission File**: Instructions on how to interpret and use the submission file generated by the model.

## Requirements
- Python 3
- Libraries:
  - pandas
  - scikit-learn

## Usage
1. **Clone the Repository**:
   ```
   git clone https://github.com/UnbeatableBann/vaccine-uptake-prediction.git
   cd vaccine-uptake-prediction
   ```

2. **Install Dependencies**:
   ```
   pip install -r requirements.txt
   ```

3. **Run the Code**:
   ```
   python vaccine_prediction.py
   ```

4. **Interpret Results**:
   - The script will generate a submission file (`submission.csv`) in the specified directory.
   - This file contains predicted probabilities for each respondent ID regarding their likelihood of receiving XYZ and seasonal vaccines.

## Contributors
- [Shadab Jamadar](https://github.com/UnbeatableBann)

