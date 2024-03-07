# Shinkansen Travel Experience Prediction

This project is dedicated to predicting whether a passenger was satisfied with their travel experience on the Shinkansen Bullet Train in Japan. Utilizing machine learning models, the goal is to analyze various factors contributing to passenger satisfaction and predict future passengers' satisfaction levels.

## Overview

The Shinkansen, also known as the Bullet Train, is a high-speed train service in Japan. Passenger satisfaction can vary based on numerous factors, including on-time performance, seating comfort, and overall service quality. This project aims to use data analytics and machine learning to predict passenger satisfaction levels.

## Dataset

The dataset includes information from two main sources:

- **Traveldata:** Contains information about the travel details of passengers.
- **Surveydata:** Contains feedback from passengers regarding various aspects of their travel experience.

Both datasets are divided into training and test sets, with the `Overall_Experience` variable indicating passenger satisfaction available in the training set.

## Features

Key features analyzed in this project include:

- Demographic details of passengers
- Travel class and distance
- Delays in departure and arrival
- Passenger ratings on various service aspects

## Models

Several machine learning models were trained to predict passenger satisfaction, including:

- LightGBM
- XGBoost
- Random Forest

## Installation

To run this project, you will need Python and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- missingno
- statsmodels
- scipy
- hyperopt
- lightgbm
- xgboost
- scikit-learn

Most of these can be installed via pip:

```bash
pip install pandas numpy matplotlib seaborn missingno statsmodels scipy hyperopt lightgbm xgboost scikit-learn
```

## Usage

To use this project, clone the repository and run the Jupyter notebook:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
   
2. Navigate to the project directory:
   
   ```bash
   cd Shinkansen-Passenger-Satisfaction-Prediction
   ```
   
3. Run Jupyter notebook:

   ```bash
   jupyter notebook
   ```
   Open the `MIT Program Hackathon.ipynb` notebook and execute the cells to train the models and make predictions.


