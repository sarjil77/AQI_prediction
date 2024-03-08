# Air Quality Forecasting of Nairobi

This project focuses on forecasting the air quality of Nairobi, specifically measuring the PM2.5 reading. The data used for this project is sourced from OpenAfrica and contains around 500,000 readings.

## Overview

The goal of this project is to forecast the PM2.5 reading in Nairobi using three different models: Linear Regression, AutoRegression, and ARIMA (AutoRegressive Integrated Moving Average). The ARIMA model includes hyperparameter tuning to improve forecasting accuracy.

Due to computational and timing constraints, the models are trained using data from only one month.

PM2.5 (particulate matter 2.5 micrometers or smaller) reading refers to the concentration of fine particles suspended in the air that are 2.5 micrometers in diameter or smaller. These particles can come from various sources such as vehicle emissions, industrial processes, construction activities, wildfires, and natural sources like dust and pollen.

PM2.5 particles are particularly concerning because of their small size, which allows them to penetrate deep into the lungs and even enter the bloodstream. This can lead to a range of health problems, including respiratory issues, cardiovascular diseases, and other adverse health effects.

## Technologies Used

- MongoDB: Used as the database to store and manage the air quality data.
- Python Libraries:
  - pandas: Data manipulation and analysis.
  - numpy: Mathematical operations on arrays and matrices.
  - pymongo: Python driver for MongoDB, used for interacting with the database.
  - statsmodels.graphics.tsaplots: Plotting tools for time series analysis.
  - statsmodels.tsa.arima.model: Implementation of ARIMA model.
  - sklearn.linear_model: Implementation of Linear Regression model.

## Project Structure

The project is structured as follows:

- `data`: Contains the datasets used for training and testing.
- `models`: Includes the implementations of the Linear Regression, AutoRegression, and ARIMA models.
- `utils`: Utility functions for data preprocessing, visualization, and evaluation.
- `notebooks`: Jupyter notebooks for data exploration, model training, and evaluation.
- `README.md`: This file, providing an overview of the project.

## Usage

To use this project:

1. Clone the repository.
2. Ensure all dependencies are installed by running `pip install -r requirements.txt`.
3. Set up MongoDB and import the air quality data.
4. Run the Jupyter notebooks in the `notebooks` directory to explore the data, train the models, and evaluate their performance.


**tip**
Try to read this project from Linear and then AutoReg and atlast ARIMA beacuase i have tried to explain every terms from basic. So if you read project from in between and you may not get that particualr terms.

