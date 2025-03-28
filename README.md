# UK Net Zero Forecasting

## Aim
This project explores a dataset containing information on patient's health in relation to diabetes. Columns include information such as patient's age, BMI, insulin levels while also declaring their diabetes diagnosis status. This project produces a model that aims to determine a patient's diabetes status by reviewing their health record.

## Overview
The project begins with some exploratory data analysis through data visualisations such as bar charts, box plots and a correlation matrix to spot trends in the data and highlight inconsistencies. It then preprocesses the data to ensure it is fit for modelling by replacing null values (in this case zeros) with appropriate averages. Finally, it builds an artificial neural network comprised of an input layer, two hidden layers, a regularisation layer and an output layer which gains an accuracy score of 75.94%.

## Notes
While doing this project I found that using too many hidden layers or neurons lead to overfitting, so I made sure to keep the model simple enough so that the results were accurate.
