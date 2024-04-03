## Calories Burnt Prediction Project

## Description
This project aims to predict the number of calories burnt by an individual based on various parameters such as duration, intensity, and individual characteristics. It utilizes a machine learning model built with Python, leveraging libraries like Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost, and Seaborn for data manipulation, visualization, and model building.


## Installation

Instructions on setting up the project environment:


```bash
# Clone the repository
git clone https://github.com/jasdeepbajaj/ML_CalorieBurntPredictionModel.git

# Navigate to the project directory
cd ML_CalorieBurntPredictionModel

# Install the requirements
pip install -r requirements.txt

# Run the Jupyter notebook
jupyter notebook calories_burnt_prediction.ipynb
```
## Data

The project utilizes two main datasets:

- exercise.csv: Contains data about different user's Gender, Age, Height, Weight, Duration, Heart_Rate, Body_Temp
- calories.csv: Records the calories burnt during each exercise session by various individuals.

## Model

The core of this project is a machine learning model built using XGBoost, trained on the provided datasets to predict calories burnt. The model's performance is evaluated using standard metrics and visualized using Matplotlib and Seaborn.

## Features

- Data preprocessing and cleaning
- Exploratory data analysis
- Model training and evaluation
- Prediction of calories burnt using exercise data

## Dependencies 
- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
- seaborn

These dependencies are also listed in the requirements.txt file.

## Documentation

Refer to the comments and markdown cells within the calories_burnt_prediction.ipynb notebook for detailed documentation on the project's methodology and implementation.