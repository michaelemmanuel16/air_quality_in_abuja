# Air Quality in Abuja Nigeria: Predicting PM2.5 Readings Using An AutoRegression Model

## Overview
This project aims to predict PM2.5 readings in Abuja, Nigeria, using an AutoRegression (AR) model. The data used in this project was obtained from Africa Open Data (https://africaopendata.org/), and it includes hourly readings of PM2.5 levels in Abuja from 2016 to 2021.

## Requirements
The following packages are required to run this project:

numpy
pandas
matplotlib
statsmodels
scikit-learn
You can install them using pip:
```
bash
pip install numpy pandas matplotlib statsmodels scikit-learn
```
## Project Structure
data/: This directory contains the raw data downloaded from Africa Open Data.
auto-regression-model.ipynb: This file contains the Jupyter notebooks used for data cleaning, exploratory data analysis, and model building.
README.md: This file.
## Conclusion
In this project, I successfully built an AR model to predict PM2.5 readings in Abuja, Nigeria. The model shows good predictive power when predictions were compared with actual readings from y_test. However, there is still room for improvement, and future work could include exploring different types of models or incorporating additional features to improve the accuracy of the predictions