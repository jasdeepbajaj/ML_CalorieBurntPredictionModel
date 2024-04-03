## Calories Burnt Prediction Project

## Description
In today's health-conscious world, effectively monitoring and managing calorie output is essential for sustaining a healthy lifestyle. Recognizing the influence of different activities and personal factors on calorie consumption is critical for those aiming to reach their fitness objectives. With the power of data science, this project seeks to tackle this challenge in health and wellness.

This initiative is positioned within the realm of Regression Machine Learning Problems. Our chief aim is to craft a predictive model for estimating calories burned. By examining a mix of input variables—ranging from the type of Exercise's duration and intensity, to personal attributes such as age, weight, and gender—we aspire to devise a model that precisely predicts the calories expended during a particular activity. This predictive model is designed to equip individuals, fitness aficionados, and health professionals with insightful data to fine-tune their strategies for calorie management and physical activity scheduling.

It utilizes a machine learning model built with Python, leveraging libraries like Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost, and Seaborn for data manipulation, visualization, and model building.


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

The core of this project is a machine learning model built using XGBoostRegressor, trained on the provided datasets to predict calories burnt. The model's performance is evaluated using standard metrics and visualized using Matplotlib and Seaborn.

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