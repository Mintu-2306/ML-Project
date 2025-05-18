# ML-Project
## Predicting Fuel Efficiency Using Multiple Linear Regression

This project aims to predict the fuel efficiency of cars using a multiple linear regression model.The dataset used for this project is the ['cars.csv'](./cars.csv), file. The project involves data cleaning, feature selection, model training, and evaluation using various metrics.

## Table of Contents
-[Overview](#overview)
- [Dataset](#dataset)  
- [Requirements](#requirements)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Model Evaluation](#model-evaluation)   
- [Contributing](#contributing)  
 

## Overview

This project utilizes multiple linear regression to analyze the impact of various features on car fuel efficiency. The workflow includes:

- Data Cleaning (handling missing values and duplicates)
- Exploratory Data Analysis (EDA)
- Feature Selection using Recursive Feature Elimination (RFE)
- Model Training and Evaluation
  
## Dataset  
The dataset used is ['cars.csv'](./cars.csv), which contains information about various car attributes such as:

- Numerical Variables: ('Dimensions.Height', 'Dimensions.Length', 'Dimensions.Width',
       'Engine Information.Number of Forward Gears',
       'Fuel Information.City mpg', 'Fuel Information.Highway mpg',
       'Identification.Year',
       'Engine Information.Engine Statistics.Horsepower',
       'Engine Information.Engine Statistics.Torque')
- Categorical Variables: ('Engine Information.Driveline', 'Engine Information.Engine Type',
       'Engine Information.Transmission', 'Fuel Information.Fuel Type',
       'Identification.Classification', 'Identification.ID',
       'Identification.Make', 'Identification.Model Year')

## Requirements
The project is implemented in Python and uses the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation
To run this project, clone the repository and install the required dependencies:
```bash
git clone https://github.com/Mintu-2306/ML-Project.git
cd ML-Project
pip install -r requirements.txt
```

## Usage
1.Place the ['cars.csv'](./cars.csv) dataset in the project directory.
2.Run the Jupyter Notebook to see the analysis and model evaluation:
```bash
 jupyter notebook ML_PROJECT.ipynb
```
## Model Evaluation
The model is evaluated using the following metrics:
- Mean Squared Error(MSE)
- R-Squared(R²) Score
  
## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.




