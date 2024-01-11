
# Combined Cycle Power Plant (CCPP) Regression Project

## Overview
This Jupyter notebook, titled `CCPP_regression.ipynb`, is dedicated to a course project focusing on a Combined Cycle Power Plant (CCPP). The project involves the development and evaluation of a machine learning model using a dataset about CCPP. The primary goal is to predict the net hourly electrical energy output based on various ambient variables.

## Author
- Marius Kalder
- Email: info@prodowner.de

## Project Instructions
1. Apply new knowledge in the modeling process to develop and evaluate a machine learning model.
2. Execute essential steps in the modeling process, including training and assessing the model.
3. Prepare a brief video presentation (maximum 5 minutes) demonstrating the modeling approach, featuring a demo or screenshot of the model, and explaining the model's evaluation method.

## Grading Criteria
1. **Modeling Approach**: Identification of the type of modeling task, features to use, and possible algorithms.
2. **Model Building**: Comparison of at least two different models using validation set or cross-validation.
3. **Model Evaluation**: Setting a reasonable evaluation metric and calculating it on the test set.
4. **Model Interpretation**: Correct interpretation and clear communication of the model's performance.

## Dataset Description
The dataset contains hourly average ambient variables:
- Temperature (T)
- Ambient Pressure (AP)
- Relative Humidity (RH)
- Exhaust Vacuum (V)
- Net hourly electrical energy output (PE) - Target variable

## Libraries Used
To run this notebook, the following libraries are required:
- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For machine learning models and evaluation metrics. This includes:
  - `LinearRegression`
  - `DecisionTreeRegressor`
  - `RandomForestRegressor`
  - `train_test_split`
  - `mean_absolute_error`
  - `mean_squared_error`

## Installation
Install the required libraries using pip:
```
pip install numpy pandas scikit-learn
```

## Structure of the Notebook
The notebook is structured into various sections, including data exploration, preprocessing, model development, and evaluation. Each section is documented to facilitate understanding and reproducibility.

## Usage
To use this notebook:
1. Ensure you have Jupyter Notebook installed and running.
2. Open `CCPP_regression.ipynb` in Jupyter Notebook.
3. Run the cells in order to execute the analysis and model development.

