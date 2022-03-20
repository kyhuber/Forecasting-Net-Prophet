# Forecasting Net Prophet

This app uses financial and user data from MercatoLibre to analyze and predict patterns. Through the findings, MercadoLibre can create business strategies to fuel groth.

## Technologies

The Forecasting Net Prophet app is written in Python 3.10.1 using Google Colab.
Pandas libraries are used to collect, prepare, and analyze the data.
Forecasting capabilities are provided by Facebook Prophet.
HVPlot is the primary tool for rendering data visualizations.

## Overview of the App

First, the app seeks to analyze Google search data and determine whether there is a pattern linking this data to corporate financial events. Next, hourly search data is grouped and considered for whether there are specific times of day where search data peaks. Along with search data, the app reads in stock price data and compares it with time series search data. Lastly, the app analyzes and forecasts patterns in the hourly search data. Plots are rendered throughout the app to visualize trends.

## Usage

Google Colab is the preferred IDE for working with Facebook Prophet.

* Save this GitHub repository to your desktop
* Run the Jupyter Notebook file in [Google Colab](https://colab.research.google.com/) 

## Contributors

The Forecasting Net Prophet app was written by Kyle Huber in March 2022. Lucas Manning provided code review.
