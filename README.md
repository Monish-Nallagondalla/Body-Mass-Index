# BMI Prediction Project

This repository contains a Python-based project that demonstrates the application of linear regression to predict BMI (Body Mass Index) using height, weight, and %Fat data.

## Dataset

The dataset used for this project includes the following columns:
- **Height M**: Height in meters
- **Weight kg**: Weight in kilograms
- **%Fat**: Percentage of body fat
- **BMI**: Body Mass Index

The dataset has 92 entries with no missing values.

## Project Overview

The project workflow includes:
1. **Data Loading**: Reading the dataset from a CSV file using pandas.
2. **Exploratory Data Analysis (EDA)**: Examining the dataset's structure, dimensions, and summary statistics.
3. **Feature Selection**: Selecting Height, Weight, and %Fat as features for prediction.
4. **Correlation Analysis**: Calculating the correlation matrix to understand relationships between variables.
5. **Linear Regression Model**: 
   - Splitting the dataset into training and testing subsets using `train_test_split`.
   - Training a Linear Regression model using `scikit-learn`.
   - Predicting BMI values for the test dataset.

## Results

The trained Linear Regression model provides:
- Coefficients: `[-23.13253634, 0.39059514, 0.02978248]`
- Intercept: `36.17193597059446`

### Example Predictions
Predicted BMI values for the test set:
```
[17.94329468, 17.92766818, 25.56526463, 19.86361112, 19.18270288,
 16.58529907, 16.09578515, 24.02504249, 21.15377744, 18.45031435,
 18.12501121, 17.74800998, 19.10781841, 22.53370891, 27.74060172,
 20.13060872, 23.79695677, 18.87850109, 20.10509283]
```

## Requirements

To run the project, the following libraries are required:
- pandas
- numpy
- scikit-learn

## Usage

1. Clone this repository.
2. Place your dataset (`BMIPY.csv`) in the specified directory.
3. Run the notebook to train the model and make predictions.

## License

This project is licensed under the MIT License.
