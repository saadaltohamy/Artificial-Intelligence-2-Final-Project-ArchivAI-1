# Car Price Prediction

This project aims to predict car prices using various machine learning models. The dataset includes various features such as brand, vehicle model, manufacturing year, type, rating, and more.

## Project Structure

```.
├── car_price.ipynb        # Main notebook with analysis and models
├── requirements.txt       # Python dependencies
├── test.csv               # Test dataset
└── train.csv              # Training dataset
```

## Requirements

The project requires the following Python packages:

- pandas
- matplotlib
- numpy
- seaborn
- scikit-learn
- fuzzywuzzy
- xgboost
- lightgbm
- catboost

You can install the required packages using the following command:

```sh
pip install -r requirements.txt
```

## Notebook Overview

The notebook ``car_price.ipynb``

 contains the following main sections:

1. **Data Loading and Cleaning**:
    - Load the training and test datasets.
    - Clean the data by handling missing values and outliers.

2. **Feature Engineering**:
    - Create new features such as the age of the car.

3. **Data Preprocessing**:
    - Encode categorical features.
    - Scale numerical features.

4. **Model Training**:
    - Train various machine learning models including Decision Tree, Random Forest, Gradient Boosting, XGBoost, LightGBM, and CatBoost.
    - Use stacking to combine the predictions of multiple models.

5. **Prediction and Submission**:
    - Make predictions on the test dataset.
    - Save the predictions to a CSV file for submission.

## Usage

To run the notebook, open ``car_price.ipynb``
in Jupyter Notebook or JupyterLab and execute the cells sequentially.

## Results

The final model uses a stacking regressor that combines multiple models to make the final prediction. 

## Contributors
- Saad Al-Tohamy
- Salma Ali
- Sohil Mohammed
- Ahmed Khaled
- Amr Shoukry
